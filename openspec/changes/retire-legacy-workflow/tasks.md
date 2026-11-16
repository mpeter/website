## 1. Migration

- [x] 1.1 Inventory files, references, branches, and PRs from origin/main.
- [x] 1.2 Archive numbered records with provenance and unchanged task states.
- [x] 1.3 Rewrite public documentation using current and historical context.
- [x] 1.4 Remove legacy command dispatch and update local agent references.
- [x] 1.5 Move constitution and update repository guidance and schema context.
- [x] 1.6 Normalize existing delta structure without losing requirements or scenarios.

## 2. Verification

- [x] 2.1 Verify constitution alignment and review the combined diff.
- [x] 2.2 Run site build, formatting, link and OpenSpec checks; report failures and repeat at final committed HEAD.
- [x] 2.3 Confirm zero retired terminology in tracked content and filenames.

### Verification limits

Build and OpenSpec checks pass. Formatting still flags 138 existing files
(the source snapshot flags 147); no newly introduced formatting failures remain.
The generated-site link check finds one pre-existing invalid anchor in the
constitution guide: `developer/#convention-packs/`. These findings are reported,
not accepted as passing gates or silently repaired outside the migration.
