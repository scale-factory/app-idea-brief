# Deep Question Bank

Use these follow-up questions when you need to go deeper on a specific topic. Don't ask all of them — pick the ones that are relevant based on what the user has told you.

## AI-powered apps

When the product has an AI/LLM component at its core:

- What does the AI actually produce? (Text, images, structured data, decisions, recommendations?)
- Does the user interact with the AI in real-time (chat-style) or does it run in the background?
- Where does the data/context come from that the AI needs? (User uploads, connected accounts, a database, live web data?)
- How good does the AI output need to be? Is "pretty good" fine or does it need human review before going out?
- Should users be able to give feedback on AI outputs to improve them? (Thumbs up/down, edit and save, regenerate?)
- Are there any AI safety or content moderation concerns? (User-generated prompts, sensitive data, regulated industry?)
- What happens when the AI gives a bad answer? What's the fallback?

## AI agents and autonomous systems

When the product is an agent that takes actions, not just a chat interface:

- What actions can the agent take autonomously? What does it actually DO?
- What tools, APIs, or systems does the agent need to connect to?
- Does it need to chain multiple steps together? (e.g., look up data → make a decision → take an action → report back)
- How should it handle errors or uncertain situations? (Stop and ask? Try again? Escalate to a human?)
- Does it run continuously, on a schedule, or on-demand?
- What does monitoring look like? How do you know it's working correctly?
- What's the human-in-the-loop requirement? Can it act fully autonomously or does someone need to approve actions?

## Marketplaces and two-sided platforms

When there are distinct buyer/seller or provider/consumer roles:

- Which side do you acquire first — supply or demand?
- What does the transaction look like? (Direct payment, booking, request-for-quote, subscription?)
- Do you take a cut? What's the fee structure?
- How do the two sides find each other? (Search, matching algorithm, browse, recommendations?)
- What trust/safety mechanisms are needed? (Reviews, verification, escrow, dispute resolution?)
- Does either side need a dashboard to manage their activity?

## Internal tools and B2B

When building for teams or organizations:

- How many users per organization, roughly?
- What roles/permissions are needed? (Admin, manager, viewer, etc.)
- Does it need to connect to tools the team already uses? (Slack, Google Workspace, Salesforce, Jira, etc.)
- Is there data that needs to be imported from an existing system? What format?
- Who's the buyer vs. the daily user? (IT admin buys, support reps use it?)
- Are there compliance requirements? (SOC 2, HIPAA, GDPR, data residency?)

## Consumer and social apps

When building for individual end users:

- How do users discover the app? (Organic search, social sharing, referrals, paid ads?)
- Is there a social or community component? (Profiles, following, sharing, commenting?)
- Are there specific screens or flows that need to work especially well on mobile?
- What's the retention hook — why does someone come back tomorrow?
- Is there user-generated content? What kind and how is it moderated?

## Data and content

When the app involves significant data handling:

- Where does the initial data come from? (User input, API imports, file uploads, scraping?)
- How much data are we talking about? (Hundreds of records, millions, real-time streams?)
- Does data need to stay in a specific region? (EU data residency, etc.)
- Who owns the data — the user, the organization, or the platform?
- Are there import/export requirements? (CSV, API, integrations?)
- Is historical data important or only current state?

## Design and UX

When visual direction matters:

- Any apps or websites you love the look and feel of? (Share links if possible.)
- Is there an existing brand — logo, colors, fonts — that this needs to match?
- Should this feel minimal/clean or feature-rich/dashboard-like?
- Any accessibility requirements? (WCAG compliance, screen reader support?)
- Dark mode needed?

