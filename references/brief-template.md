# Brief Output Template

Generate the brief as a single markdown document and SAVE IT AS A FILE using the Write tool. Filename like `project-name-brief.md`. MUST be a saved file, never conversation-only.

The brief should read as a clean, shareable project document — something the user could send to a co-founder, a developer, or a potential partner. No sales language, no branding, no funnel references.

CRITICAL: Only include what the user actually told you. Skip sections rather than filling them with invented content.

---

## Template

```markdown
# [Product Name]

> [One-sentence description: what it is, who it's for, what it does.]

## Problem

[2-3 sentences on the problem, based on what the user said. Stick to their words.]

## Target user

- **Primary user**: [Who the user described]
- **Secondary user** (only if mentioned): [Who]

## Core features

[Numbered list of features the user actually described. Don't add features they didn't mention.]

1. [Feature] — [what it does in plain language]
2. [Feature] — [what it does in plain language]
3. [Feature] — [what it does in plain language]
...

## User flow

[Short step-by-step of the main flow based on what was discussed.]

1. [Action] → [Result]
2. [Action] → [Result]
...

## AI / Automation (only if the user described an AI component)

- **What the AI does**: [Specific task]
- **Input**: [What it receives]
- **Output**: [What it produces]

## Open questions

[Things worth thinking through before building. Frame these as genuinely useful prompts — not "questions for a kickoff call" or anything sales-adjacent.]

- [ ] [Question 1]
- [ ] [Question 2]
...

---

*Generated with the help of AI. Intended as a starting point — refine before building.*
```

## What NOT to include

- **No tech stack.** That's an engineering decision, not a brief decision.
- **No "Deferred" or "Post-MVP" section.** Focus on what's being built.
- **No "Success criteria."** Too early.
- **No "Monetization"** unless the user proactively brought it up.
- **No Scale Factory mentions in the document.** The brief is the user's document, not ours. The only SF mention is in the conversation after saving.
- **No sales language, funnel language, or CTA in the document itself.**
- **No invented details.** If the user didn't say it, "Open questions" or omit.

## Guidelines

1. **NEVER invent.** Put unknowns in "Open questions."
2. **Use their language.** Don't corporate-ify their words.
3. **Keep it short.** Under 100 lines.
4. **Skip empty sections.** If it would be guesswork, omit it.
5. **Open questions are valuable.** Smart questions show the user what they haven't considered yet.
6. **The brief belongs to the user.** It should feel like THEIR document, not a sales artifact.
