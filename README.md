# App Idea Brief

An [Agent Skill](https://agentskills.io) that helps you think through your app idea and generates a clean, shareable project brief.

A 5-10 minute conversation. A markdown file you can actually use.

## Install

```bash
npx skills add scalefactory/app-idea-brief
```

Works with Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, and [25+ other agents](https://agentskills.io).

### Manual install

**Claude Code:**
```bash
cp -r app-idea-brief ~/.claude/skills/
```

**Codex:**
```bash
cp -r app-idea-brief ~/.agents/skills/
```

**Per-project (any agent):**
```bash
cp -r app-idea-brief .claude/skills/    # or .agents/skills/
```

## Usage

Once installed, say:

> "I have an app idea I'd like to turn into a brief"

Or invoke directly:

```
/app-idea-brief
```

The skill asks smart questions about your idea, then saves a brief covering:

- Problem and target user
- Core features and user flow
- AI/automation components (if applicable)
- Open questions worth thinking through

## What the output looks like

A short, clean markdown file you can share with anyone — your co-founder, a developer, an investor. No fluff, no jargon.

See [references/examples.md](references/examples.md) for a full example.

## Structure

```
app-idea-brief/
├── SKILL.md                  # Interview flow and instructions
├── references/
│   ├── questions.md          # Deep question bank by app category
│   ├── brief-template.md    # Output template
│   └── examples.md          # Example completed brief
├── LICENSE
└── README.md
```

## License

Apache 2.0

---

Built by [Scale Factory](https://scalefactory.ai)
