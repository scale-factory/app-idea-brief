# Example: Completed Brief

This is what the output should look like. Clean, shareable, no branding, no sales language. Under 100 lines. Only information the user actually provided.

---

# ReplyPilot

> An AI tool for B2B SaaS support teams that drafts responses to tickets using past conversations and knowledge base docs.

## Problem

Support agents spend most of their time writing responses to questions that have been answered before. They dig through old tickets, docs, and Slack threads to piece together answers. New hires take weeks to ramp up because the knowledge lives in people's heads.

## Target user

- **Primary user**: Customer support agents at B2B SaaS companies
- **Secondary user**: Support team leads who manage the knowledge base

## Core features

1. **Ticket inbox** — Connect to Zendesk and display tickets in a unified view
2. **AI draft generation** — Auto-generate a draft response for each ticket based on past tickets and knowledge base
3. **Knowledge base sync** — Import docs from Notion as source material for the AI
4. **Agent review flow** — Agent sees the draft, can edit or regenerate, then send
5. **Confidence scoring** — Flag low-confidence drafts for senior review

## User flow

1. Support lead connects Zendesk and imports knowledge base from Notion
2. New ticket arrives with an AI-generated draft alongside it
3. Agent reviews the draft, edits if needed, clicks "Send"
4. Response goes back to Zendesk

## AI / Automation

- **What the AI does**: Generates draft responses to support tickets
- **Input**: Incoming ticket + customer history + relevant knowledge base content
- **Output**: Draft response with citations to source material

## Open questions

- [ ] Should drafts generate when a ticket arrives or when an agent opens it? (Cost vs. speed tradeoff)
- [ ] What happens when the knowledge base has no relevant content for a ticket?
- [ ] Should agents see which knowledge base articles the AI referenced?
- [ ] Zendesk has email tickets and live chat — support both or just email to start?
- [ ] Any analytics needs? (Acceptance rate, time saved, etc.)
- [ ] How should the knowledge base stay in sync as Notion docs change?

---

*Generated with the help of AI. Intended as a starting point — refine before building.*
