## MODIFIED Requirements

### Requirement: Divisor Page Enhancement

The Divisor page MUST include a "Why a Council?" section explaining the architectural rationale for multi-perspective evaluation, structural doer/judge separation, and layered feedback.

#### Scenario: Visitor reads council rationale

- **GIVEN** a visitor opens the Divisor page
- **WHEN** they read "Why a Council?"
- **THEN** the section explains multi-perspective evaluation, structural doer/judge separation, and layered feedback

### Requirement: Constitution Page Enhancement

The Constitution page SHOULD include a note on the governance hierarchy (constitution > convention packs > agent personas > commands > CI) and decay resistance.

#### Scenario: Visitor reads governance context

- **GIVEN** a visitor opens the Constitution page
- **WHEN** they read the governance note
- **THEN** the note describes the governance hierarchy and decay resistance

### Requirement: Knowledge Page Enhancement

The Knowledge page SHOULD include context framing Dewey as part of the three-tier context system and as a feedforward control.

#### Scenario: Visitor reads knowledge context

- **GIVEN** a visitor opens the Knowledge page
- **WHEN** they read the Dewey context
- **THEN** the context frames Dewey within the three-tier context system and as a feedforward control

### Requirement: Developer Page Enhancement

The convention packs section SHOULD note that convention packs function as feedforward controls and portable harness templates.

#### Scenario: All pages build successfully

- **GIVEN** the four pages are modified with small additions
- **WHEN** `npm run build` is executed
- **THEN** the build completes successfully
