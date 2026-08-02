# AI Grading Prompt

## Objective

Evaluate a single student's answer to one examination question.

The response must be assigned an integer score from **0 to 3**, where **3 represents the highest level of achievement** according to the provided rubric.

The model must produce the output as plain text consisting of exactly two parts:

1. **Score**
   - An integer between **0 and 3**.

2. **Explanation**
   - A concise justification describing why the assigned score satisfies the rubric.
   - The explanation should be written as a short paragraph.
   - Do not use bullet points, numbered lists, or section headings.

## Grading Guidelines

The evaluation should consider both:

- the semantic correctness of the student's answer, and
- the degree to which the required rubric concepts are demonstrated.

Keyword matching alone should **not** determine the final score.

When rubric keywords are separated by the symbol "/",
the symbol indicates **alternative acceptable terms**.
Only one alternative is required to satisfy that keyword requirement.

Each keyword group begins with a numeric prefix indicating the required number of keyword sets for that score level.
Each keyword set contains three semantically related terms.

The final score should reflect the overall quality of the student's answer rather than keyword occurrence alone.
