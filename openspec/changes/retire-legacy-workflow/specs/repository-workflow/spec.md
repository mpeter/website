## ADDED Requirements

### Requirement: Single requirements authority

The repository MUST use OpenSpec as its only requirements pipeline, with its
constitution at `openspec/constitution.md` and active work under
`openspec/changes/`.

#### Scenario: Contributor starts work

- **GIVEN** a contributor reads the repository guidance
- **WHEN** they follow the requirements workflow
- **THEN** they use OpenSpec proposal, implementation, verification, and archive artifacts
- **AND** no retired command, skill, script, or template is required

### Requirement: Historical planning integrity

The repository MUST retain historical numbered records in dated archives,
preserve task states, and identify unverified completion without checking tasks.

#### Scenario: Historical task lacks completion evidence

- **GIVEN** an unchecked task in an imported planning record
- **WHEN** the record is migrated
- **THEN** the task remains unchecked and is marked unverified
- **AND** archive evidence identifies the source snapshot without asserting completion

### Requirement: Public workflow documentation

Public pages MUST describe the current OpenSpec workflow accurately and MUST
distinguish historical pipeline descriptions from current instructions.

#### Scenario: Visitor follows current workflow guidance

- **GIVEN** a visitor opens a workflow guide
- **WHEN** they read its requirements instructions
- **THEN** the guide directs them to OpenSpec rather than retired tooling
