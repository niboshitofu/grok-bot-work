# AGENTS.md

## Repository role

`niboshitofu/grok-bot-work` is the application target for Grok Bot handoffs that originate from `niboshitofu/ai-work-hub`.

It is a placeholder application repository. Do not invent an application architecture, product design, or implementation beyond that role unless a later handoff explicitly asks for it.

## How to work here

- Treat work as hub-driven. Scope, task identity, and acceptance criteria come from the private hub `niboshitofu/ai-work-hub`.
- Keep this repository privacy-safe. Do not copy Luna or organization confidential content, personal data, secrets, credentials, or private transcripts into commits, pull requests, issues, or files.
- Do not describe the hub as public, and do not paste hub-only material in order to document a task.
- Leave repository visibility unchanged unless a handoff explicitly says otherwise.
- Empty-repository hygiene (README, agent guidance, and similar repo metadata) is in scope. Application features are not, until a handoff asks for them.

## Out of scope by default

- Implementing application source, CI, or product architecture
- Renaming the repository or changing its visibility
- Editing hub task state (for example `TASK.md` in `niboshitofu/ai-work-hub`)
