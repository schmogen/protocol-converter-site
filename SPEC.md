# PDF → Word Protocol Converter (MVP Spec)

## Goal
User uploads a PDF + enters email → receives or downloads a converted DOCX.

## MVP User Flow
1. User clicks “Try it now”
2. Upload section appears
3. User selects a PDF and enters email
4. User clicks Convert
5. System shows status (uploading / converting / done / error)
6. User downloads DOCX

## Constraints
- Max file size: 20MB
- Input: PDF only
- Output: DOCX
- No authentication for MVP
- Files are not stored permanently

## Technical Rules
- Do NOT rewrite the existing conversion logic
- Wrap existing conversion code with minimal glue code
- One command to run locally
- Clear error handling for invalid files

## Acceptance Criteria
- End-to-end conversion works locally
- Landing page triggers conversion
- Converted DOCX downloads successfully
- Errors are visible to the user
