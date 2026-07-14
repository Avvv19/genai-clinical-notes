# GenAI Clinical Notes - Design Concept

This repository is an architecture proposal for converting transcript or text input into structured clinical-document drafts. It currently contains documentation only; no application code, tests, deployment, clinical validation, or EHR integration is implemented.

## Proposed workflow

1. Accept approved synthetic or de-identified text input.
2. Extract candidate clinical entities and required note sections.
3. Generate a typed draft for a selected document format.
4. Run required-field, omission, and unsupported-statement checks.
5. Present the draft to a qualified reviewer for correction and approval.
6. Optionally map approved output into a FHIR-compatible structure.

## Intended evaluation

- Required-section completeness
- Omission and unsupported-statement rates
- Reviewer corrections and review time
- Code-suggestion precision
- FHIR validator results
- Privacy-aware logging and access-control checks

## Safety and status

This is a personal design concept, not a medical device or clinical application. It does not diagnose, recommend treatment, replace a qualified reviewer, provide billing codes for operational use, or establish compliance with any healthcare regulation. Any future implementation should use synthetic or explicitly approved data and require human approval for every output.

## Future work

- Add typed schemas and synthetic fixtures
- Implement a minimal local pipeline
- Add unit tests for required fields and unsupported statements
- Add a FHIR validation path
- Document a threat model and data-retention boundary

No placeholder code has been added solely to make the concept appear implemented.
