# .github

Org-wide community health files and GitHub profile for the [AEGIS Initiative](https://github.com/aegis-initiative).

---

## What This Repo Does

Files in this repository are automatically inherited by all repos in the `aegis-initiative` org that don't define their own versions. This is a [GitHub special repository](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

This repository is also the source of truth for shared GitHub-native collaboration assets across the org:

- default community health files
- default issue and pull request templates
- reusable GitHub Actions workflow entrypoints that other repos invoke with `uses:`

## Contents

| File | Purpose |
|---|---|
| `profile/README.md` | Org profile displayed on the GitHub org page |
| `CODE_OF_CONDUCT.md` | Contributor Covenant v2.1 |
| `CONTRIBUTING.md` | Org-wide contributing guidelines |
| `SECURITY.md` | Security vulnerability reporting policy |
| `TRADEMARKS.md` | AEGIS trademark usage guidelines |
| `.github/pull_request_template.md` | Default PR template |
| `.github/ISSUE_TEMPLATE/` | Default issue templates (bug, docs, feature, question, RFC) |
| `.github/CODEOWNERS` | Ownership for this repo |
| `.github/dependabot.yml` | Dependabot configuration |

## Overriding Defaults

Any repo can override these defaults by creating its own version of the file. For example, `aegis-governance` has its own `SECURITY.md` with repo-specific security considerations.

---

## Standards

All community health files follow standards defined in [aegis](https://github.com/aegis-initiative/aegis) — the central authority for the AEGIS ecosystem.

Operational infrastructure, deployment assets, and runbooks live in [`aegis-ops`](https://github.com/aegis-initiative/aegis-ops). This repo owns GitHub-level defaults and reusable GitHub workflow entrypoints; `aegis-ops` owns runtime operations.

---

*AEGIS™ and "Capability without constraint is not intelligence™" are trademarks of Finnoybu IP LLC.*
