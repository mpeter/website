## Why

Requirements need one authority. Retire the previous pipeline while retaining
historical planning records and their original completion states.

## What Changes

- Archive 22 numbered planning records with provenance, without claiming completion.
- Move the constitution to `openspec/constitution.md` and use OpenSpec exclusively.
- Remove retired local commands, scripts, templates, and skills; update their callers.
- Update public documentation and normalize existing delta spec structure.

## Capabilities

### New Capabilities

- `repository-workflow`: One requirements authority with preserved planning history.

### Modified Capabilities

- None. This repository publishes a static website, not a command installer.

## Impact

Local agent instructions and website Markdown change. No application code,
dependency versions, release version, or remote branches change. Existing
unfinished tasks remain unfinished. Historical references are phrased neutrally.

## Constitution Alignment

- **I. Content Accuracy — PASS:** Preserve historical states and distinguish
  historical descriptions from current OpenSpec instructions.
- **II. Minimal Footprint — PASS:** Remove the redundant local pipeline; use
  existing Markdown and OpenSpec rather than new machinery.
- **III. Visitor Clarity — PASS:** Provide one current workflow without changing
  page navigation or presentation.
