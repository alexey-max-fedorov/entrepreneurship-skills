# AGENTS.md

Guidelines for AI agents working in this repository.

## Repository Overview

This repository contains **Agent Skills** for AI agents following the [Agent Skills specification](https://agentskills.io/specification.md). Skills install to `.agents/skills/` (the cross-agent standard). This repo also serves as a **Claude Code plugin marketplace** via `.claude-plugin/marketplace.json`.

- **Name**: Entrepreneurship Skills
- **GitHub**: [alexey-max-fedorov/entrepreneurship-skills](https://github.com/alexey-max-fedorov/entrepreneurship-skills)
- **Creator**: Alexey Fedorov
- **License**: MPL-2.0 for `skills/`, MIT for the template (see `LICENSE`)

## Repository Structure

```
entrepreneurship-skills/
├── .claude-plugin/        # Claude Code plugin.json + marketplace.json
├── .codex-plugin/         # Codex plugin.json
├── .agents/plugins/       # Codex marketplace.json
├── .github/               # Workflows, issue and PR templates, sync script
├── skills/                # Agent Skills
│   └── skill-name/
│       ├── SKILL.md       # Required skill file
│       ├── references/    # Optional detail docs
│       └── evals/         # Optional evals.json
├── scripts/               # check-versions.mjs, package_skills.py
├── tests/                 # Validator regression + repo script tests
├── CONTRIBUTING.md
├── LICENSE
├── README.md
└── VERSIONS.md
```

## Build / Lint / Test Commands

**Skills** are content-only (no build step). Verify manually:
- YAML frontmatter is valid
- `name` field matches directory name exactly
- `name` is 1-64 chars, lowercase alphanumeric and hyphens only
- `description` is 1-1024 characters

**Repo scripts and tests:**
```bash
node scripts/check-versions.mjs          # Version consistency
./validate-skills.sh                     # Frontmatter validation
bash tests/run-regression.sh             # Validator regression tests
node --test tests/scripts/*.test.cjs     # Sync and version script tests
python3 -m unittest discover -s tests -p test_skill_packaging.py -v
```

## Versioning

Two version layers, with different rules:

**Repo release version** — `.claude-plugin/plugin.json` `version`, `.claude-plugin/marketplace.json` `metadata.version`, and the `VERSIONS.md` changelog headings all share one x.y.z number:

- **x** — repo-wide changes (restructures, spec changes, breaking changes)
- **y** — new skill(s) added
- **z** — updates to existing skills

Do not bump y for content added to an existing skill, no matter how substantial — that's a z release (e.g. a new reference file in alpha is 0.2.0 → 0.2.1, not 0.3.0).

**Per-skill version** — `metadata.version` in each SKILL.md, mirrored in the `VERSIONS.md` table. Bump on ANY shipped change to that skill: the update check compares `VERSIONS.md` against users' local skill metadata, so an unbumped change is invisible to installed users. Minor for new capability or description triggers, patch for fixes and clarifications.

Bump the repo release version in the same PR that ships the change (skipping this leaves the manifests out of step with the skills).

CI enforces both layers on PRs. Fetch first so `origin/master` is current, then run it locally before pushing:

```bash
node scripts/check-versions.mjs --base origin/master
```

It fails if a changed skill didn't bump `metadata.version`, if `VERSIONS.md` disagrees with any SKILL.md, if the repo version didn't bump (or has no `### x.y.z` block), or if a file in `references/` isn't linked from anywhere in its skill. Changes only under a skill's `evals/` don't need a bump, since they don't change what installed users get.

## Agent Skills Specification

Skills follow the [Agent Skills spec](https://agentskills.io/specification.md).

### Required Frontmatter

```yaml
---
name: skill-name
description: What this skill does and when to use it. Include trigger phrases.
---
```

### Frontmatter Field Constraints

| Field         | Required | Constraints                                                      |
|---------------|----------|------------------------------------------------------------------|
| `name`        | Yes      | 1-64 chars, lowercase `a-z`, numbers, hyphens. Must match dir.   |
| `description` | Yes      | 1-1024 chars. Describe what it does and when to use it.          |
| `license`     | No       | License name (default: MIT)                                      |
| `metadata`    | No       | Key-value pairs (author, version, etc.)                          |

### Name Field Rules

- Lowercase letters, numbers, and hyphens only
- Cannot start or end with hyphen
- No consecutive hyphens (`--`)
- Must match parent directory name exactly

**Valid**: `alpha`, `beta`, `my-skill`
**Invalid**: `Alpha-Skill`, `-skill`, `my--skill`

### Optional Skill Directories

```
skills/skill-name/
├── SKILL.md        # Required - main instructions (<500 lines)
├── references/     # Optional - detailed docs loaded on demand
├── scripts/        # Optional - executable code
└── assets/         # Optional - templates, data files
```

## Writing Style Guidelines

### Structure

- Keep `SKILL.md` under 500 lines (move details to `references/`)
- Use H2 (`##`) for main sections, H3 (`###`) for subsections
- Use bullet points and numbered lists liberally
- Short paragraphs (2-4 sentences max)

### Tone

- Direct and instructional
- Second person ("You are an expert in [domain]")
- Professional but approachable

### Formatting

- Bold (`**text**`) for key terms
- Code blocks for examples and templates
- Tables for reference data
- No excessive emojis

### Clarity Principles

- Clarity over cleverness
- Specific over vague
- Active voice over passive
- One idea per section

### Description Field Best Practices

The `description` is critical for skill discovery. Include:
1. What the skill does
2. When to use it (trigger phrases)
3. Related skills for scope boundaries

```yaml
description: When the user wants to do X. Use when the user says "trigger one," "trigger two." For adjacent job Y, see beta.
```

## Claude Code Plugin

This repo also serves as a plugin marketplace. The manifest at `.claude-plugin/marketplace.json` lists all skills for installation via:

```bash
/plugin marketplace add alexey-max-fedorov/entrepreneurship-skills
/plugin install entrepreneurship-skills
```

See [Claude Code plugins documentation](https://code.claude.com/docs/en/plugins.md) for details.

## Git Workflow

### Branch Naming

- New skills: `feature/skill-name`
- Improvements: `fix/skill-name-description`
- Documentation: `docs/description`

### Commit Messages

Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

- `feat: add skill-name skill`
- `fix: improve clarity in alpha`
- `docs: update README`

### Pull Request Checklist

- [ ] `name` matches directory name exactly
- [ ] `name` follows naming rules (lowercase, hyphens, no `--`)
- [ ] `description` is 1-1024 chars with trigger phrases
- [ ] `SKILL.md` is under 500 lines
- [ ] No sensitive data or credentials

## Checking for Updates

When using any skill from this repository:

1. **Once per session**, on first skill use, check for updates:
   - Fetch `VERSIONS.md` from GitHub: https://raw.githubusercontent.com/alexey-max-fedorov/entrepreneurship-skills/master/VERSIONS.md
   - Compare versions against local skill files

2. **Only prompt if meaningful**:
   - 2 or more skills have updates, OR
   - Any skill has a major version bump (e.g., 1.x to 2.x)

3. **Non-blocking notification** at end of response:
   ```
   ---
   Skills update available: X skills have updates.
   Say "update skills" to update automatically, or run `git pull` in your entrepreneurship-skills folder.
   ```

4. **If user says "update skills"**:
   - Run `git pull` in the entrepreneurship-skills directory
   - Confirm what was updated

## Claude Code-Specific Enhancements

These patterns are **Claude Code only** and must not be added to `SKILL.md` files directly, as skills are designed to be cross-agent compatible (Codex, Cursor, Windsurf, etc.). Apply them locally in your own project's `.claude/skills/` overrides instead.

### Dynamic content injection with `!`command``

Claude Code supports embedding shell commands in SKILL.md using `` !`command` `` syntax. When the skill is invoked, Claude Code runs the command and injects the output inline — the model sees the result, not the instruction.

**Most useful application: auto-inject a shared context file**

Instead of every skill telling the agent "go check if `.agents/context.md` exists and read it," you can inject it automatically:

```markdown
Project context: !`cat .agents/context.md 2>/dev/null || echo "No context file found — ask the user about their situation before proceeding."`
```

Place this at the top of a skill's body (after frontmatter) to make context available immediately without any file-reading step.

**Other useful injections:**

```markdown
# Inject today's date for recency-sensitive skills
Today's date: !`date +%Y-%m-%d`

# Inject current git branch (useful for workflow skills)
Current branch: !`git branch --show-current 2>/dev/null`

# Inject recent commits for context
Recent commits: !`git log --oneline -5 2>/dev/null`
```

**Why this is Claude Code-only**: Other agents that load skills will see the literal `` !`command` `` string rather than executing it, which would appear as garbled instructions. Keep cross-agent skill files free of this syntax.
