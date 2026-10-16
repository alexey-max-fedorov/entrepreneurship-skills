# Contributing

Thanks for your interest in contributing to Entrepreneurship Skills! This guide will help you add new skills or improve existing ones.

## Requesting a Skill

You can also suggest new skills by [opening a skill request](https://github.com/alexey-max-fedorov/entrepreneurship-skills/issues/new?template=skill-request.yml).

## Adding a New Skill

The fastest start is to copy `skills/alpha/`, which shows the expected structure.

### 1. Create the skill directory

```bash
mkdir -p skills/your-skill-name
```

### 2. Create the SKILL.md file

Every skill needs a `SKILL.md` file with YAML frontmatter:

```yaml
---
name: your-skill-name
description: When to use this skill. Include trigger phrases and keywords that help agents identify relevant tasks.
---

# Your Skill Name

Instructions for the agent go here...
```

Optional frontmatter fields: `license` (default: MIT), `metadata` (author, version, etc.)

### 3. Follow the naming conventions

- **Directory name**: lowercase, hyphens only (e.g., `alpha`)
- **Name field**: must match directory name exactly
- **Description**: 1-1024 characters, include trigger phrases

### 4. Structure your skill

```
skills/your-skill-name/
├── SKILL.md           # Required - main instructions
├── references/        # Optional - additional documentation
│   └── guide.md
├── scripts/           # Optional - executable code
│   └── helper.py
└── assets/            # Optional - templates, images, data
    └── template.json
```

### 5. Write effective instructions

- Keep `SKILL.md` under 500 lines
- Move detailed reference material to `references/`
- Include step-by-step instructions
- Add examples of inputs and outputs
- Cover common edge cases

## Improving Existing Skills

1. Read the existing skill thoroughly
2. Test your changes locally
3. Keep changes focused and minimal
4. Bump `metadata.version` in the SKILL.md and the `VERSIONS.md` row, and bump the repo version (see `AGENTS.md`)
5. Run `node scripts/check-versions.mjs`

## Licensing

Contributions under `skills/` are licensed MPL-2.0 (see `skills/LICENSE`). Contributions to the rest of the repository are MIT.

## Submitting Your Contribution

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-skill-name`)
3. Make your changes
4. Test locally with an AI agent
5. Submit a pull request using the appropriate template (append `?template=<name>.md` to the PR URL to pre-fill it):
   - [New Skill](.github/PULL_REQUEST_TEMPLATE/new-skill.md) — `?template=new-skill.md`
   - [Skill Update](.github/PULL_REQUEST_TEMPLATE/skill-update.md) — `?template=skill-update.md`
   - [Documentation](.github/PULL_REQUEST_TEMPLATE/documentation.md) — `?template=documentation.md`

## Skill Quality Checklist

- [ ] `name` matches directory name
- [ ] `description` clearly explains when to use the skill
- [ ] Instructions are clear and actionable
- [ ] No sensitive data or credentials
- [ ] Follows existing skill patterns in the repo

## Questions?

Open an issue if you have questions or need help with your contribution.
