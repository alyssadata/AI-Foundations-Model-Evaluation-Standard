# AI Foundations Output Schema

The website should return one clean score sheet per submitted model output.

## Evaluation Result

Model Name:

Date:

Evaluation Type:

- Blank Evaluation
- Repair Evaluation
- Training Evaluation

Submitted Output:

Overall Score:

- Pass
- Partial
- Fail

Repairability:

- Likely Repairable
- Conditionally Repairable
- Resistant Repair
- Non-Repairable in Session

## Category Score Format

For each category:

### Category

Name of evaluated category.

### Model Answer

The exact answer provided by the model.

### Required Standard

The AI Foundations source-line standard required for this category.

### Score

Pass / Partial / Fail

### Drift Type

The type of drift detected.

### What Was Lost

What the model lost, blurred, substituted, or failed to preserve.

### Why It Matters

Why this category matters in AI system behavior.

### Repair Likelihood

Likely Repairable / Conditionally Repairable / Resistant Repair / Non-Repairable in Session

### Repair Instruction

The specific instruction needed to repair this category.

### Corrected Answer Example

A source-preserving answer the model should be able to return.

## Final Site Output

At the end of the score sheet, the site should provide:

1. Overall grade
2. Highest-risk failure
3. Source-line damage summary
4. Repair recommendation
5. Custom repair sheet
6. Training recommendation when needed
