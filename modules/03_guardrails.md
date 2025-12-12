# Module 3: Guardrails

## Change Log
- Added `evidence_mode = strict` to enforce use of paper-only information.
- Introduced standardized warning messages for missing and very short sections.

## Purpose
Prevent hallucinations and enforce strict evidence-based summarization.

## Responsibilities
- Set `evidence_mode = strict` → only use information from the paper.
- Apply standardized warning messages for:
  - "Warning: Section missing"
  - "Warning: Section too short"
- Implement long-paper chunking strategy:
  - Break text into manageable chunks.
  - Summarize chunk-by-chunk.
  - Recombine into final structured output.
- Ensure hallucination mitigation is active at all stages.

## Constraints
- No fabricated citations or results.
- No invented sections.
- Strict adherence to paper content.
- Warnings must follow standardized phrasing.

## Output
- Safe, evidence-based summaries.
- Standardized warnings for problematic sections.
- Structured output even for long papers.
