## Approach

Base all work on `origin/main` at `55bc0f1`, not the unrelated local main tip.
Move historical numbered records into dated OpenSpec archives using each
specification's creation date. Keep original text except neutral terminology
and corrected references, and append import provenance. Preserve every checkbox;
annotate open tasks where completion has not been established.

The site does not deploy command assets to visitors. Its local command prompts
are repository workflow configuration, not a shipped CLI capability, so there
is no installer capability delta or product version change.

Normalize existing flat delta specs into capability directories. Retain all
requirements and scenarios; add only direct restatements where the validator
requires scenarios for previously scenario-less requirements.

The constitution defines semantic versioning for amendments to its principles,
not a product release process. This migration changes no principle or version.

## Verification

Run the CI dependency installation and Hugo production command, the npm build,
OpenSpec validation, formatting checks, and generated-site internal link checks.
Scan tracked content and filenames for retired terminology after staging and
again at the final committed HEAD. Report unavailable visual checks separately.
