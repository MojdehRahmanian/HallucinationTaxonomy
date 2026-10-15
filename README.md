# HallucinationTaxonomy
Replication package for the paper *"Tracing Hallucinations in LLM-Generated UML Class Diagrams: An Empirical Taxonomy and Mitigation Study"*.

## Overview

This study investigates hallucinations in reasoning-capable LLMs generating UML class diagrams from natural-language requirements. We propose an empirical taxonomy of 11 hallucination sub-types organised into three dimensions:

- **Prompt Faithfulness (A1–A4):** Deviations between requirements and reasoning.
- **Code Faithfulness (B1–B4):** Discrepancies between reasoning and generated PlantUML.
- **Reasoning Quality (C1–C3):** Problems within the reasoning process.

We analyse hallucination distributions, investigate associations with reasoning length and requirement complexity, and evaluate taxonomy-guided mitigation strategies.

## Repository Structure

| Directory | Contents |
|---|---|
| `Data/` | Study-specific datasets, and processed data |
| `Prompts/` | Generation, annotation, and mitigation prompts |
| `Figures/` | Figures used in the paper |
| `Result/` | Experimental results |
| `*.ipynb` | Analysis notebooks for reproducing the results |
