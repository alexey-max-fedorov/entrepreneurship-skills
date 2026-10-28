# Entrepreneurship Skills

Agent Skills for entrepreneurs, packaged as one plugin that works in both Claude Code and Codex. The same `skills/` directory serves both.

Built on the open [Agent Skills specification](https://agentskills.io/specification.md).

## Skills

<!-- SKILLS:START -->
| Skill | Description |
|-------|-------------|
| [business-model](skills/business-model/) | Designs, documents, assesses, and stress-tests business models: how a business creates, delivers, and captures value.... |
| [creative-ideation](skills/creative-ideation/) | Generates and organizes solution ideas through brainstorming, reverse thinking, mind mapping, collaboration, and the... |
| [customer-ecosystem](skills/customer-ecosystem/) | Maps the customer ecosystem, the network of stakeholders (end user, decision maker, economic buyer, influencer,... |
| [customer-end-user-profile-and-persona](skills/customer-end-user-profile-and-persona/) | Builds a research-based End User Profile (the fictional, specific user inside a defined segment) and turns it into a... |
| [customer-interview](skills/customer-interview/) | Plans, scripts, conducts, and synthesizes customer interviews using ten interview rules, an annotated interview guide,... |
| [customer-segmentation](skills/customer-segmentation/) | Customer entry point. Answers who is my customer: segment a broad market into groups that share a need, behavior, or... |
| [customer-validation](skills/customer-validation/) | Tests a venture's assumptions about the problem, the customer/market, and the solution with real customers before more... |
| [financials](skills/financials/) | Builds, reads, forecasts, and audits basic business financials in plain founder terms: income statement (P&L), cash... |
| [market-research](skills/market-research/) | Plans, runs, and judges market research: primary vs. secondary sources, qualitative vs. quantitative data, method... |
| [opportunity-id](skills/opportunity-id/) | Finds, digs into, and screens business opportunities, meaning problems worth solving for profit. Covers idea vs.... |
| [pricing-models](skills/pricing-models/) | Recommends, defends, and tests a price. Covers what determines price, the right price from customer, business, and... |
| [problem-statement](skills/problem-statement/) | The library entry point and starting point for any venture. Finds, diagnoses, writes, tests, and validates the problem... |
| [value-proposition](skills/value-proposition/) | Builds, audits, and sharpens a value proposition: the statement of what benefit you provide, for whom, and how you do... |
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
pnpx skills add alexey-max-fedorov/entrepreneurship-skills
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

See [CONTRIBUTING.md](CONTRIBUTING.md). In short: copy an existing skill such as `skills/problem-statement/` to `skills/<your-skill>/`, rewrite it, add a row to `VERSIONS.md`, then run:

```bash
bun scripts/check-versions.mjs
./validate-skills.sh
```

## License

Skills (`skills/`) are [MPL-2.0](skills/LICENSE). The template scaffolding around them is MIT, derived from [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills). See [LICENSE](LICENSE).
