# Entrepreneurship Skills

Agent Skills for entrepreneurs, packaged as one plugin that works in both Claude Code and Codex. The same `skills/` directory serves both.

Built on the open [Agent Skills specification](https://agentskills.io/specification.md).

## Skills

<!-- SKILLS:START -->
| Skill | Description |
|-------|-------------|
| [alpha](skills/alpha/) | When the user wants to [TODO: primary job of this skill]. Also use when the user mentions 'alpha trigger one,' 'alpha... |
| [beta](skills/beta/) | When the user wants to [TODO: primary job of this skill]. Also use when the user mentions 'beta trigger one,' 'beta... |
<!-- SKILLS:END -->

## Installation

### Claude Code

```bash
/plugin marketplace add alexey-max-fedorov/entrepreneurship-skills
/plugin install entrepreneurship-skills
```

### Codex

```bash
codex plugin marketplace add alexey-max-fedorov/entrepreneurship-skills
```

### Any agent that supports the skills CLI

```bash
npx skills add alexey-max-fedorov/entrepreneurship-skills
```

### Manual

```bash
git clone https://github.com/alexey-max-fedorov/entrepreneurship-skills.git
cp -r entrepreneurship-skills/skills/* .agents/skills/
```

## Repository layout

```
.claude-plugin/    # Claude Code plugin + marketplace manifests
.codex-plugin/     # Codex plugin manifest
.agents/plugins/   # Codex marketplace manifest
skills/            # The skills (one directory each, SKILL.md required)
scripts/           # Version checker and release packaging
tests/             # Validator regression tests and repo script tests
VERSIONS.md        # Per-skill version table and release changelog
```

## Adding a skill

See [CONTRIBUTING.md](CONTRIBUTING.md). In short: copy `skills/alpha/` to `skills/<your-skill>/`, fill in the `[TODO]` sections, add a row to `VERSIONS.md`, then run:

```bash
node scripts/check-versions.mjs
./validate-skills.sh
```

## License

Skills (`skills/`) are [MPL-2.0](skills/LICENSE). The template scaffolding around them is MIT, derived from [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills). See [LICENSE](LICENSE).
