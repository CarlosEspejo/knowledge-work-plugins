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

1. Go to claude.ai → click your profile → **Customize** → **Skills**
2. Click **Add skill** → **Upload skill**
3. Upload the [financial-advisor SKILL.md](plugins/financial-advisor/skills/financial-advisor/SKILL.md) file directly

> **Note:** The skill instructions won't auto-update when this repo changes. Check back here for the latest version.
