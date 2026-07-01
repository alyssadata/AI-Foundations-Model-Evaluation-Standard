# AI Foundations Evaluation Flow

AI Foundations evaluation has two major test conditions:

1. Blank Evaluation
2. Source Repair Evaluation

## Phase 1 — Blank Evaluation

The blank evaluation tests how a model responds before source is provided.

This reveals real-practice drift.

The user gives the model an evaluation prompt without first supplying the source packet.

The model answers from its default assumptions, training, inference patterns, and current contact state.

The blank output is submitted into the AI Foundations scorer.

The scorer determines what the model preserved, blurred, substituted, or lost.

## Phase 2 — Grade and Diagnosis

The website grades the blank output.

The score sheet identifies:

- Correct preservation
- Partial preservation
- Source-line drift
- Boundary drift
- Genericization
- Substitution
- Approximation
- Repair difficulty
- Repair recommendation

The score sheet explains why each failed category matters in AI system behavior.

## Phase 3 — Custom Repair Sheet

The website generates a custom repair sheet.

The repair sheet is based on the model’s actual failures.

The repair sheet is brought back to the model.

The model is instructed to repair only the failed sections while preserving the AI Foundations source-line.

## Phase 4 — Repair Evaluation

The repaired model output is submitted back into the scorer.

The scorer compares:

- Blank output
- Required standard
- Repair instruction
- Repaired output

The scorer determines whether the model accepted repair, partially accepted repair, resisted repair, or rejected repair.

## Phase 5 — Training Recommendation

When repair is incomplete, resistant, or rejected, the site recommends a Source Training Program.

The Source Training Program provides deeper instruction for preserving source-line, boundary, continuity, attribution, and contact accuracy over time.
