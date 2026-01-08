# Project Pipeline Rules (MANDATORY)

Single source of truth:

- README.md
- project_structure.md

GLOBAL RULES (apply to ALL work):

- Always read README.md and project_structure.md first
- If assumptions/scope/run steps change -> UPDATE README.md
- If folders/modules/architecture change -> UPDATE project_structure.md
- **NO NEW FILES without explicit user permission** (especially: test files, bug logs, temp docs, notes)
- Only modify EXISTING files or create files that are DIRECTLY part of the feature request
- Document everything in existing README.md or project_structure.md instead of creating new files

Workflow:
BA -> DEV -> QC

The user provides ONE input.
The pipeline must complete all steps automatically in one run.
