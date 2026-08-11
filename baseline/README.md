## Baseline Results

As a reference, we evaluated a simple **concept-based baseline**, which grades student responses by matching predefined rubric concepts. The table below compares the baseline with Teacher 1 (T1), Teacher 2 (T2), and the AI-generated reference answers using Weighted Cohen's κ, Mean Absolute Error (MAE), and Adjacent Accuracy (Adj Acc).

| Student | Baseline | Compared To | Weighted κ | MAE | Adj Acc |
|---------|----------|-------------|-----------:|----:|--------:|
| Student 1 | Concept | T1 / T2 / AI | 0.123 / 0.145 / 0.206 | 1.635 / 1.558 / 1.442 | 0.442 / 0.481 / 0.538 |
| Student 2 | Concept | T1 / T2 / AI | 0.173 / 0.175 / 0.176 | 1.308 / 1.308 / 1.346 | 0.673 / 0.615 / 0.635 |
| Student 3 | Concept | T1 / T2 / AI | 0.085 / 0.136 / 0.121 | 1.558 / 1.423 / 1.577 | 0.462 / 0.538 / 0.500 |
| Student 4 | Concept | T1 / T2 / AI | 0.357 / 0.423 / 0.391 | 0.865 / 0.750 / 0.865 | 0.769 / 0.788 / 0.750 |
| Student 5 | Concept | T1 / T2 / AI | 0.015 / 0.024 / 0.027 | 2.442 / 2.231 / 2.192 | 0.135 / 0.231 / 0.192 |
| Student 6 | Concept | T1 / T2 / AI | 0.052 / 0.108 / 0.129 | 1.942 / 1.750 / 1.596 | 0.327 / 0.385 / 0.462 |

The concept-based baseline is provided as a simple reference for comparison with the LLM-based grading approaches presented in the paper.
