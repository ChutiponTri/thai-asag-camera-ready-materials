# Evaluation Protocol

## Objective

To evaluate the robustness of LLM-based Automated Short Answer Grading (ASAG) systems under both standard and adversarial response conditions.

---

## Phase 1 — Model Screening

Purpose

Identify the most suitable candidate models for the main experiment.

Procedure

1. Prepare the context dataset.
2. Generate synthetic student responses.
3. Evaluate all candidate models.
4. Compare performance across Bloom's Taxonomy levels.
5. Select the two highest-performing model families.

Output

Selected models for Phase 2.

---

## Phase 2 — Adversarial Evaluation

Procedure

1. Construct the final 55-question test set.
2. Prepare teacher rubrics.
3. Create six student profiles.
4. Grade all responses using the selected LLMs.
5. Grade all responses independently by two professional Thai teachers.
6. Compare human and AI grading.

---

## Evaluation Metrics

The following metrics were computed.

• Weighted Cohen's Kappa

• Mean Absolute Error (MAE)

• Adjacent Accuracy (±1)

• Exact Match

• Krippendorff's Alpha
