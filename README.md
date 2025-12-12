**CISC101-Group64-PaperSummarizer**
-
---
**Project Overview**
-

This repository contains our **Research Paper Summarizer project** for CISC101.  
The goal of this project is to design a modular LLM-based system that can summarize academic papers, generate expert and layperson summaries, extract citation（student created), and highlight biases or limitations(student created).

This project builds upon the **modular architecture we designed in PS2 (TravelPlanner)**, adapting the same framework to a new context: summarizing research papers.

---
**Flow chart**
-

START ↓ 
Intake & Setup → Normalize sections 
↓ 
Section Loop → Summarize each section (short/detailed) + citaion & Bias & Limitation Detect
↓ 
Guardrails → Strict evidence mode + warnings 
↓
Rendering & Refinement → Final structure 
↓ Citation Extractor → Extract references 
↓ 
Bias & Limitation Detector
↓ 
OUTPUT → Summary + Table + Glossary + Warnings END

---
**Verification paragraph**
-

The generated system prompts fully meet our PS2 specification design requirements. 
It includes all necessary inputs, outputs, and constraints. The internal architecture comprises four core modules. 
The modular design draws inspiration from the TravelPlanner framework, ensuring clarity, reproducibility, and scalability.

---
## Contributors
- Group 64, CISC101  
- Members: Litang Liang, Yichi Zhang
