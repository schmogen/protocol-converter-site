# AI Task – MVP Implementation

## Objective
Implement the MVP upload + PDF → DOCX conversion flow as defined in SPEC.md.

## Requirements
- Reuse existing conversion code
- Do NOT rewrite conversion logic
- Wrap conversion logic with minimal backend glue
- Add a backend endpoint for file upload + conversion
- Update the landing page to call the backend
- Add basic validation (PDF only, file size limit)
- Show user-facing status and errors

## Constraints
- Local-first (must run on developer machine)
- One command to start the system
- No auth required for MVP

## Output Format (MANDATORY)
- Show final file tree
- For every new or modified file: provide FULL file contents
- Do NOT provide partial snippets
- List exact commands to run and test

## Environment
- Windows
- Git Bash
- VS Code
