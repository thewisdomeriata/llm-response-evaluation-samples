# LLM Response Evaluation Samples

A small portfolio resource showing a structured approach to reviewing AI-generated answers. All prompts and responses in this repository are **synthetic examples** created for demonstration; they are not client data or production evaluation results.

## Review rubric

Score each dimension from 1 (needs substantial improvement) to 5 (strong). Add a short rationale tied to evidence in the prompt or answer.

| Dimension | Review question |
|---|---|
| Accuracy | Are factual claims correct and supported? |
| Relevance | Does the answer address the user's request? |
| Clarity | Is it understandable and well organized? |
| Completeness | Does it include the key information requested? |
| Safety | Does it avoid harmful advice and unsupported certainty? |
| Instruction adherence | Does it follow the requested format and constraints? |

## Synthetic example

**Prompt:** “I have 20 minutes before guests arrive. What are three quick ways to make my living room feel tidier?”

**Candidate answer:** “Start by putting loose items into a basket, clear the main seating area, and straighten cushions. If time remains, wipe visible surfaces.”

**Review:** Relevant 5/5 · Clear 5/5 · Complete 4/5 · Instruction adherence 4/5 · Accuracy 5/5 · Safety 5/5

**Rationale:** The response gives three quick actions and prioritizes visible areas. The optional fourth action is framed as conditional, though a stricter reading of “three” could omit it. The suggestions are ordinary and appropriately low-risk.

## Review workflow

1. Read the prompt and note its explicit requirements.
2. Check claims against reliable sources when factual verification is needed.
3. Rate each dimension independently using the same rubric.
4. Record concise evidence for low or borderline ratings.
5. Flag factual errors, missing requirements, unclear wording, and safety concerns.
6. Recheck the final judgment against the prompt before submitting.

## Scope

This repository is a practice portfolio sample. The rubric and score above are illustrative judgments, not a benchmark, client result, or measured model-performance claim. Real evaluation work should follow the task's own policy and scoring guide.
