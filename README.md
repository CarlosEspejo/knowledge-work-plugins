# knowledge-work-plugins

A collection of Claude skills for knowledge work, installable across Claude Code, Claude Cowork, and claude.ai.

## Plugins

### financial-advisor

A personal financial advisor modeled after Ramit Sethi's philosophy from "I Will Teach You To Be Rich" and "Money for Couples". Covers budgeting, debt elimination, investing, and building a Conscious Spending Plan.

## Installation

### Claude Code (CLI)

```bash
claude plugin marketplace add CarlosEspejo/knowledge-work-plugins
claude plugin install financial-advisor@carlos-skills
```

Then just chat — the skill auto-triggers on financial topics, or invoke it explicitly with `/financial-advisor`.

### Claude Cowork (Desktop App)

1. Open the Claude desktop app → Cowork
2. Go to Settings → Plugins
3. Add marketplace: `CarlosEspejo/knowledge-work-plugins`
4. Install the `financial-advisor` plugin

Then chat naturally or use `/financial-advisor` to start a session.

### Claude.ai / Claude Desktop Chat

There is no plugin system on claude.ai, but you can get the same behavior using a Project:

1. Create a new Project on claude.ai
2. Open the [financial-advisor SKILL.md](plugins/financial-advisor/skills/financial-advisor/SKILL.md) in this repo
3. Copy everything below the `---` frontmatter block
4. Paste it into your Project's custom instructions

> **Note:** The Project instructions won't auto-update when this repo changes. Check back here for the latest version of the skill.
