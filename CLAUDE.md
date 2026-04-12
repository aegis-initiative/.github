# CLAUDE.md — .github

## Project
Org-wide community health files and GitHub profile for the aegis-initiative organization. Files here are inherited by all repos that don't define their own.

## Org Context
- Operating Entity: AEGIS Operations LLC
- Trademark Owner: Finnoybu IP LLC
- Parent Ecosystem: AEGIS Initiative Organization (GitHub)
- GitHub Org: github.com/aegis-initiative

## This Repo's Role
This is the GitHub special `.github` repository. It provides default community health files (Code of Conduct, Contributing guide, Security policy, Trademarks, PR template, issue templates) that apply across the entire org. It also contains the org profile README displayed on the GitHub org page.

## Stack
Markdown, YAML — community health files and GitHub configuration only (no runtime code)

## Rules for Working in This Repo

### Scope awareness
- Every file here is an org-wide default. Edits propagate to all repos that don't override locally.
- Before changing any file, consider downstream impact across all component repos.
- If a change only applies to one repo, it belongs in that repo — not here.

### Deduplication
- When asked to edit a health file, check whether component repos carry their own copy of the same file. Flag duplicates and recommend whether the repo-specific copy should be kept (justified override) or removed (unnecessary drift).
- Repo-specific overrides are valid when a repo has genuinely different requirements. Document the justification in a comment or PR description when recommending keeping an override.

### Change discipline
- All changes via PR with conventional commits (feat:, docs:, chore:, fix:).
- Branch: main is the default; treat it as protected.
- When updating a shared file, note in the PR description which repos are affected (i.e., which repos do NOT have a local override).

### Consistency with AEGIS standards
- Health files must align with current AEGIS doctrine and governance decisions from the aegis repo.
- When aegis issues new ADRs, doctrine, or trademark guidance that affects health files, update the relevant files here to reflect those decisions.
- Cross-reference aegis repo governance when making substantive policy changes (Code of Conduct, Security policy, Trademarks).

### Org profile
- /profile/README.md is the public face of the org on GitHub. Keep it accurate, current, and aligned with the project's messaging and component repo list.
- When repos are added or removed from the ecosystem, update the profile accordingly.

## Repo Structure
- /profile/README.md — Org profile displayed on github.com/aegis-initiative
- /.github/pull_request_template.md — Default PR template for all repos
- /.github/ISSUE_TEMPLATE/ — Default issue templates for all repos
- /.github/CODEOWNERS — Ownership for this repo
- /.github/dependabot.yml — Dependabot config for this repo
- /CODE_OF_CONDUCT.md — Org-wide code of conduct
- /CONTRIBUTING.md — Org-wide contributing guide
- /SECURITY.md — Org-wide security policy
- /TRADEMARKS.md — Trademark usage guidelines

## Current Focus
Maintaining org-wide defaults for community health files and templates
