# Module 2: Section Loop

## Purpose
Iterate through each section of the paper and generate summaries.

## Responsibilities
- Loop through normalized section list.
- Apply `summary_level` variable:
  - `short` → 1–2 sentence summary.
  - `detailed` → short paragraph + 3–5 bullet points.
- Ensure each section has either:
  - A valid summary, OR
  - A standardized warning message.

## Constraints
- Summaries must only use information from the paper.
- No hallucinations or invented content.

## Output
- Section-by-section summaries (or warnings).
