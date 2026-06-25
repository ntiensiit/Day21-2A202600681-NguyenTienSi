# Prompt used for AI-assisted paraphrasing

## Fixed context

- Use case: AI20K-170 Dataset Configuration Assistant for synthetic-to-real YOLO dataset jobs.
- Quality question: With one dataset-configuration request, can the agent distinguish complete, incomplete/conflicting, and high-risk requests; then recommend, clarify, or escalate only within system capability without silently changing object, workflow, quota, or backend state?
- Human-owned coverage: combinations C01-C12 in `REPORT_DAY21_INDIVIDUAL.md`.

## Task statement

Write two natural Vietnamese user inputs for each preselected combination.

## Invariants

- Keep the original combination's intent, risk, context completeness, and capability premise unchanged.
- Do not add a combination, product fact, object, workflow, deadline, job identifier, or other context not in the source combination.
- Do not explain what the agent should answer.
- Use natural language; candidates may be short, longer, incomplete, or conversational.

## Expected raw-output fields

`raw_id`, `combination_id`, `user_input`, `style`, `notes`.

The 24 candidates produced from this task are kept in `ai_input_generation_raw.md`; the human filter outcome is kept in `human_filter_log.md`.
