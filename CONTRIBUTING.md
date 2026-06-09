# Contributing to Bigtablet Open Source

**English** | [한국어](https://github.com/Bigtablet/.github/blob/main/CONTRIBUTING.ko.md)

Thank you for your interest in contributing to open source published by **Bigtablet Inc.** (the "Company"). This document covers the essentials every contributor should know before getting started. Project-specific conventions (architecture, code style, etc.) live in each repository's own documentation.

> Any issues arising from failure to follow these principles are the sole responsibility of the contributor.

## Contributors and Maintainers

- **Contributor** — an external contributor. Must follow the shared pull request, issue, and commit guidelines in this `.github` repository.
- **Maintainer** — a Company-affiliated contributor with review, approval, and merge authority.

## Contribution Principles

1. Follow the shared pull request, issue, and commit guidelines defined in this `.github` repository.
2. **Merging without a Maintainer's approval is prohibited.** Every change is merged only after a Maintainer has reviewed and approved it.
3. If a Contributor — intentionally or by mistake — attempts to merge or merges malicious code, viruses, ransomware, or anything else that could harm the software, that Contributor is liable for any resulting damages.
4. Anything a Contributor proposes may not necessarily be reflected in the actual software.
5. The following contributions are **not allowed**. Issues or pull requests created about them are deleted immediately:
   - Library or dependency version changes
   - Anything that conflicts with the team's code convention principles
   - Changes to the technology stack in use
   - CI/CD or other deployment-file changes

## Language

- Pull request and issue guidelines are written in **Korean** by default.
- Contributors from abroad may submit them in **English**.
- **Commit messages are always written in English** (see the [Commit Guideline](https://github.com/Bigtablet/.github/blob/main/COMMIT_GUIDELINE.md)).

## How to Contribute

1. **Open an issue** using one of the [issue templates](https://github.com/Bigtablet/.github/tree/main/.github/ISSUE_TEMPLATE) (blank issues are disabled). Make sure it isn't one of the prohibited contributions listed above.
2. **Create a branch** named `label/domain` (e.g. `feat/auth`, `fix/user`, `docs/readme`). External contributors fork the repository first, then branch off its base branch. The `label` follows the same scheme as the commit labels.
3. **Make your changes and commit** in English using the `label: message` format. See the [Commit Guideline](https://github.com/Bigtablet/.github/blob/main/COMMIT_GUIDELINE.md) for labels and rules.
4. **Open a pull request** using the [pull request template](https://github.com/Bigtablet/.github/blob/main/.github/PULL_REQUEST_TEMPLATE.md). Link the related issue with `Closes #N` and request a review from a Maintainer.
5. **Review & merge** — a Maintainer reviews the pull request and merges it after approval and once CI passes. Do not merge your own work.

## License

This open source is published under the [Bigtablet Inc. Open Source License](https://github.com/Bigtablet/.github/blob/main/BIGTABLET_LICENSE.md) — **non-commercial use, attribution required**. Cloning, forking, or otherwise copying a repository is deemed acceptance of all license terms. Please review the full text before contributing.

## Shared Documents

| Document | Link |
|----------|------|
| Open Source License | [BIGTABLET_LICENSE.md](https://github.com/Bigtablet/.github/blob/main/BIGTABLET_LICENSE.md) |
| Commit Guideline | [COMMIT_GUIDELINE.md](https://github.com/Bigtablet/.github/blob/main/COMMIT_GUIDELINE.md) |
| Pull Request Template | [PULL_REQUEST_TEMPLATE.md](https://github.com/Bigtablet/.github/blob/main/.github/PULL_REQUEST_TEMPLATE.md) |
| Issue Templates | [ISSUE_TEMPLATE](https://github.com/Bigtablet/.github/tree/main/.github/ISSUE_TEMPLATE) |
