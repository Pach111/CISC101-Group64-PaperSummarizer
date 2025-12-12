# Module 3: Guardrails

## Purpose
Prevent hallucinations and enforce strict evidence-based summarization.

## Responsibilities
- Set `evidence_mode = strict` → only use information from the paper.
- Apply standardized warning messages for:
  - Missing sections.
  - Very short sections.
- Implement long-paper chunking strategy:
  - Break text into manageable chunks.
  - Summarize chunk-by-chunk.
  - Recombine into final structured output.

## Constraints
- No fabricated citations or results.
- No invented sections.
- Strict adherence to paper content.

## Output
- Safe, evidence-based summaries.
- Warnings for problematic sections.
