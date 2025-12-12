# Module 1: Intake & Setup

## Purpose
Normalize the section list and prepare the summarizer for structured processing.

## Responsibilities
- Accept user inputs:
  - Research paper text (PDF/Markdown)
  - Section list
  - Target audience (expert/layperson)
- Normalize the section list (standardize naming, order).
- Detect missing sections.
- Detect very short sections (below threshold length).

## Constraints
- Do not invent sections.
- Do not fabricate results.
- Each section must either have a summary or a warning.

## Output
- Cleaned section list.
- Flags for missing or short sections.
