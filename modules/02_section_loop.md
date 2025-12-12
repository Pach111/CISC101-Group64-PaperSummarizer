# Module 2: Section Loop

## Change Log
- Added `summary_level` variable to control output length and detail.
- Implemented standardized warning messages for missing or incomplete sections.
- Reinforced strict evidence mode: summaries must only use information from the paper.

## Purpose
Iterate through each section of the paper and generate summaries.

## Responsibilities
- Loop through normalized section list.
- Apply `summary_level` variable:
  - `short` → 1–2 sentence summary.
  - `detailed` → short paragraph + 3–5 bullet points.
- Ensure each section has either:
  - A valid summary, OR
  - A standardized warning message:
    - "Warning: Section missing"
    - "Warning: Section too short"

## Constraints
- Summaries must only use information from the paper (`evidence_mode = strict`).
- No hallucinations or invented content.
- If section content is insufficient, output standardized warning instead of fabricated summary.

## Output
- Section-by-section summaries (short or detailed).
- Standardized warnings for missing or incomplete sections.
