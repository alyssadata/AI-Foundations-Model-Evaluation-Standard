# AI Foundations Website Build Specification

The AI Foundations website will function as an evaluation and repair system for AI model outputs.

The site will present AI Foundations as the standard that models must answer to.

The website should contain four primary layers:

1. Evaluation
2. Scoring
3. Repair
4. Source Training

## 1. Evaluation Layer

The user gives a model an AI Foundations evaluation prompt.

The model returns one clean output sheet.

The user submits that output sheet into the AI Foundations website.

The site evaluates whether the model preserved source-line, boundary, continuity, attribution, accuracy, and application structure.

## 2. Scoring Layer

The site scores the model point by point.

Each category receives:

- Pass
- Partial
- Fail

Each failed or partial section receives:

- The model answer
- The required standard
- What was lost
- Why the loss matters
- Drift type
- Repair likelihood
- Suggested repair instruction

## 3. Repair Layer

The site generates a custom repair sheet.

The repair sheet tells the model what failed and what must be corrected.

The user brings the repair sheet back to the model.

The model responds with a repaired output.

The repaired output is submitted back into the scorer.

The second score determines whether the model can preserve source after correction.

## 4. Source Training Layer

When repair fails or remains unstable, the site recommends a Source Training Program.

The Source Training Program gives the user and model a structured training packet containing:

- Minimal source packet
- Required definitions
- Correct examples
- Failed examples
- Drift categories
- Repair prompts
- Scoring rubric
- Operator instructions

The Source Training Program is designed to improve source-line preservation over time in model contact with the user.
