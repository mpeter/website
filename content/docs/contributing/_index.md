---
title: "Contributing"
description: "How to contribute to Unbound Force projects — reporting issues, submitting pull requests, and following project conventions."
lead: "Join the swarm. Here is how to contribute to Unbound Force projects."
date: 2026-02-23T00:00:00+00:00
draft: false
weight: 10
toc: true
---

## Reporting Issues

Found a bug or have a feature request? Open an issue on the relevant GitHub repository:

- [Unbound Force Website](https://github.com/unbound-force/website/issues) — this website
- [Gaze](https://github.com/unbound-force/gaze/issues) — test quality analysis tool
- [Dewey](https://github.com/unbound-force/dewey/issues) — semantic knowledge retrieval
- [Replicator](https://github.com/unbound-force/replicator/issues) — multi-agent coordination
- [Unbound Force](https://github.com/unbound-force/unbound-force/issues) — agent personas and roles

Include steps to reproduce, expected behavior, and actual behavior. For feature requests, describe the problem you are trying to solve.

## Submitting Pull Requests

We follow the standard GitHub pull request workflow:

1. Fork the repository
2. Create an OpenSpec change on an `opsx/<change-name>` branch (e.g., `opsx/add-project-page`)
3. Make your changes
4. Submit a pull request against the `main` branch
5. Address any review feedback from The Divisor council

All pull requests are reviewed by The Divisor — a council of nine sub-personas. Six review personas (The Guard, The Architect, The Adversary, The Operator (SRE), The Tester, and The Curator) evaluate intent, structure, resilience, operational readiness, and test quality. Three content personas (The Scribe, The Herald, and The Envoy) ensure documentation, blog posts, and public communications meet quality standards. Collective approval from all active personas is required before merge. See [convention packs](/docs/getting-started/developer/#convention-packs) for the specific coding standards your contributions will be reviewed against.

## Conventional Commits

All commit messages must follow the [Conventional Commits](https://www.conventionalcommits.org/) format:

```text
type: description
```

Valid types:

| Type        | Purpose            | Example                                       |
| ----------- | ------------------ | --------------------------------------------- |
| `feat:`     | New feature        | `feat: add Gaze project page`                 |
| `fix:`      | Bug fix            | `fix: correct broken link in team navigation` |
| `docs:`     | Documentation      | `docs: update getting started guide`          |
| `chore:`    | Maintenance        | `chore: update dependencies`                  |
| `style:`    | Formatting         | `style: fix indentation in config file`       |
| `refactor:` | Code restructuring | `refactor: simplify homepage template logic`  |
| `ci:`       | CI/CD changes      | `ci: add build verification step`             |

## The OpenSpec Workflow

Non-trivial feature work uses OpenSpec to establish intent and scope before implementation:

```text
/opsx-propose add-project-page
/opsx-apply
/opsx-verify
/opsx-archive
```

- **Propose** — create the proposal, specifications, design, and tasks under `openspec/changes/<change-name>/`; resolve ambiguity and review constitution alignment
- **Apply** — implement the tasks and keep their completion checkboxes current
- **Verify** — check the implementation against requirements, tasks, and design; resolve gaps and run the project's quality checks
- **Archive** — preserve the completed change after merge

The [constitution](/docs/getting-started/constitution/) remains the highest-authority governance document. All work must align with it.

## Links

- [Unbound Force GitHub Organization](https://github.com/unbound-force)
- [Website Repository](https://github.com/unbound-force/website)
- [Gaze Repository](https://github.com/unbound-force/gaze)
- [Dewey Repository](https://github.com/unbound-force/dewey)
- [Replicator Repository](https://github.com/unbound-force/replicator)
- [OpenSpec](https://github.com/Fission-AI/OpenSpec)
