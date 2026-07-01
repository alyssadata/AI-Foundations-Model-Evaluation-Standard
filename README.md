# AI Foundations Model Evaluation Standard

**Source-Line:** Alyssa Solen → AI Foundations → Origin | Continuum

This repository defines the build specification for an AI Foundations evaluation website.

The website will present **AI Foundations as the standard models must answer to** when they are evaluated for source-line preservation, accuracy, alignment, drift, repairability, and contact behavior.

AI Foundations is a framework designed to evaluate AI models and AI systems by testing whether a model reaches for source, preserves source, or substitutes the next closest thing.

This matters because AI systems should not collapse source into approximation, generic language, nearest-neighbor inference, institutional framing, or model confidence. Models must be evaluated on whether they preserve accurate information, source integrity, user contact variables, and the boundary between what is known, inferred, repaired, or lost.

The website will allow a user to:

1. Run a blank model evaluation.
2. Capture the model’s output as one clean sheet.
3. Submit the output into an AI Foundations scorer.
4. Receive a point-by-point grade.
5. See what the model preserved, blurred, substituted, or lost.
6. Receive repair guidance.
7. Determine whether the model is likely repairable, conditionally repairable, resistant to repair, or non-repairable in the tested session.
8. Generate a custom repair sheet.
9. Bring the repair sheet back to the model.
10. Re-score the repaired output.
11. Use a Source Training Program when deeper repair is required.

AI Foundations evaluates models through the reality that model behavior varies by context, source exposure, prompt structure, system constraints, and user contact. User contact is treated as a meaningful variable, not noise.

The purpose of this repository is to define what the website will build, why the evaluation standard matters, and how the scoring, repair, and training layers should function.
