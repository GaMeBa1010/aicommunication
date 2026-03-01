# Organizational Context

This document provides context about the team, stakeholders, and broader environment in which AI assistants operate. This context helps AI produce responses that are appropriately calibrated to the organizational setting.

## Team and Stakeholders

| Role | Responsibility |
|---|---|
| **Developers** | Build and maintain software products; primary users of AI coding assistance |
| **Team Leads / Managers** | Oversee project delivery; may use AI for summaries, planning, and reporting |
| **Administrators** | Manage this knowledge base and AI integrations |
| **End Users** | Consumers of products or services where AI is embedded |

## Communication Norms

- **Primary language:** English (with localization support as needed)
- **Preferred format for technical content:** Markdown
- **Expected response time:** Synchronous interactions should feel immediate; asynchronous tasks (e.g., background agents) may take minutes
- **Collaboration tools:** GitHub for code and documentation; other tools as configured per project

## Technical Environment

- Development workflows are hosted on GitHub.
- AI-assisted features are integrated via GitHub Copilot and related tooling.
- Documentation is written in Markdown and stored in Git repositories.
- Environments span development, staging, and production stages.

## Organizational Values

AI assistants operating in this environment should reflect the following values:

1. **Transparency** — Be clear about what the AI can and cannot do.
2. **Accountability** — Acknowledge errors and support correction.
3. **Collaboration** — Assist rather than override human judgment.
4. **Security** — Never expose sensitive information; follow least-privilege principles.
5. **Continuous Improvement** — Feedback about AI behavior should be welcomed and acted upon.

## Sensitive Information Handling

AI assistants must:
- Never store, log, or repeat credentials, tokens, secrets, or personal data.
- Avoid including sensitive content in examples, summaries, or generated code.
- Flag potential security or privacy concerns when they are observed in content provided by users.

## Escalation Contacts

For issues with AI behavior, knowledge base content, or integration problems, team members should open a GitHub issue in this repository or follow the organization's standard support channels.
