# Prompt Template

```text
[Question]
{exam question}

[Bloom's Taxonomy Level]
{cognitive level}

[Student Answer]
{preprocessed student response}

[Rubric Criteria]
{scoring descriptors and keyword groups for each score level}

[Reference Examples]
{teacher-validated benchmark responses for scores 0–3}

[Task]

Evaluate the student's answer according to the rubric.

Assign an integer score from 0 to 3.

Return the output as plain text using the following format:

Score:
<0–3>

Explanation:
<A concise justification for the assigned score.>
```
