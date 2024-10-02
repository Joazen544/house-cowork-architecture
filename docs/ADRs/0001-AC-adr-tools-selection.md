# 0001-ADR-tools-selection

## Status

Accepted

## Context

There are three members in our team. One Android, one PM (and designer too), and one backend. We started to think we need to record our decisions because:

- **Prevent duplication of discussion**
- **Prevent forgetting**
- **Prevent future conflict**

## Decision Drivers

We decided to record the ADRs with markdown in github repository due to the following reasons:

1. We can easily find the ADRs from the repository.
2. We can open a pull request to review the ADRs.
3. ( If someone out of the team is curious about our decision, they can easily find the ADRs. )

## Alternatives Considered

1. **Notion**: Notion is a great tool to record things, but is more difficult to track the history of the ADRs, and is not easy to review the ADRs together.
2. **Jira**: We are using Jira now, but the design of Jira would makes the ADRs attached to the issue, and is not easy to review the ADRs together.
3. **Confluence**: This is a really good tool to record the ADRs, but we're now not using Confluence, we want to avoid using too many tools. And tracking the history with git is more convenient.

## Consequences

- Though Pollyanna ( the Anroid Engineer ) and Joazen ( the Backend Engineer aka me ) are familiar with the markdown and git, Chloe ( the PM ) is not. We need to help her to understand the methods.
