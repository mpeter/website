---
title: "Changelog"
description: "Release history for the Unbound Force toolchain — user-facing changes per release, sourced from actual release artifacts."
lead: "User-facing changes per release."
date: 2026-05-02T00:00:00+00:00
draft: false
weight: 10
toc: true
---

## Website — Unreleased

### Changed

- OpenSpec is the website repository's sole requirements workflow. Contributor
  guides now describe proposal, implementation, verification, and archiving;
  historical planning records retain their task states in dated archives.

## v0.12.0 — 2026-04-14

### Added

- **Containerized development sessions** -- New `uf sandbox` command group for launching, managing, and extracting changes from containerized OpenCode sessions. Supports Podman (local) and Eclipse Che / Dev Spaces (CDE) backends.
- **Linux cross-platform install** -- RPM packages and Homebrew Formula for Linux installations.
- **Externalized workflow commands** -- The release externalized specification workflow and Gaze init assets from embedded assets, enabling independent updates.
- **Workflow phase boundaries** -- The release added boundaries between specification and implementation commands to prevent out-of-phase changes.

### Fixed

- Guardrails added to `/opsx-propose` to prevent phase boundary violations.
- Anthropic Vertex environment variables now forwarded to sandbox containers.
- Google Cloud config directory mounted for Vertex AI auth in sandbox.
