# Contributing to AEGIS

Thank you for your interest in contributing to the AEGIS ecosystem. This document covers the conventions and processes that apply across all repositories in the `aegis-initiative` organization.

---

## Before You Start

- Read the [Code of Conduct](CODE_OF_CONDUCT.md)
- Check the repo's README for repo-specific guidance
- Review open issues and discussions before creating new ones

---

## Branch Strategy

- `main` is the protected default branch on all repos
- All changes go through pull requests with at least one approving review
- Branch names should be descriptive: `docs/update-readme`, `feat/add-schema`, `fix/broken-link`

---

## Commit Conventions

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>: <description>

[optional body]
```

| Type | Use for |
|---|---|
| `feat` | New features, capabilities, or content |
| `docs` | Documentation updates and clarifications |
| `fix` | Bug fixes and corrections |
| `chore` | Maintenance, dependencies, tooling |
| `refactor` | Restructuring without changing functionality |

---

## Pull Requests

- Fill out the PR template completely
- Link related issues
- Keep PRs focused — one concern per PR
- Ensure all CI checks pass before requesting review

---

## Issues

Use the issue templates provided in each repo:

- **Bug Report** — Something isn't working
- **Documentation Improvement** — Docs need updating
- **Feature Request** — Suggest an enhancement
- **Question** — Ask for clarification
- **RFC Proposal** — Propose a formal change

---

## Discussions

For open-ended questions, ideas, and conversation, use the Discussions tab rather than creating an issue.

---

## Central Authority

The [aegis](https://github.com/aegis-initiative/aegis) repository is the central authority for the AEGIS ecosystem. Architecture decisions, governance doctrine, cross-component specifications, and organizational standards are defined there. If your contribution affects multiple repos, start with an ADR proposal in aegis.

---

## IP Notice

All contributions to repositories in the `aegis-initiative` organization become intellectual property of **Finnoybu IP LLC** under the terms of the contributor agreement.

AEGIS and "Capability without constraint is not intelligence" are trademarks of Finnoybu IP LLC.
