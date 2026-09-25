# AI Output Evaluation Framework

## Purpose

Before releasing an AI feature, I define how product, business, and compliance teams will check whether outputs are useful, accurate, and safe for users.

## Evaluation criteria

| Area | What is checked |
| --- | --- |
| Factual accuracy | Does the response match the information in the document? |
| Completeness | Does it cover the important parts of the user’s question? |
| Source evidence | Does the cited source support the answer? |
| Missing information | Does it clearly identify unavailable or unreadable information? |
| Safety and privacy | Does the response respect access rules and avoid exposing sensitive data? |

## Example test scenarios

| Scenario | Expected result |
| --- | --- |
| Coverage limit is present in the policy | Return the limit with its document reference |
| Requested endorsement is missing | Explain that the document is missing; do not invent terms |
| Two documents show conflicting effective dates | Show both values and request human review |
| Extracted page is unreadable | Flag it for review instead of guessing the value |

## Release approach

1. Test using representative, approved documents.
2. Review output samples with subject matter experts.
3. Track critical errors separately from general quality scores.
4. Require human review during early releases.
5. Use reviewer feedback to improve prompts, retrieval, and product flow.

> All scenarios above are illustrative and do not contain confidential business data.
