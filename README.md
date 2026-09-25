# UnderwriteAssist AI

### GenAI product case study for underwriting and claims document review

## The problem

Underwriters and claims analysts often spend significant time reviewing long policy documents, loss runs, endorsements, and claim notes. Important clauses, coverage limits, loss details, or missing documents can be overlooked during manual review.

## Product goal

Help users review insurance documents faster by providing source backed summaries, risk clause extraction, loss history comparison, and guided question answering. The user remains responsible for the final decision.

## My role

As a Senior AI Product Analyst, I worked with underwriting, claims, compliance, UX, data science, engineering, and QA teams to:

- Run discovery sessions and map current document review workflows
- Define AI use cases, PRDs, user stories, and acceptance criteria
- Design expected AI outputs, source evidence requirements, and human review steps
- Define evaluation criteria for factual accuracy, completeness, citations, and missing information handling
- Validate extracted fields and API responses using SQL and Postman during UAT
- Measure adoption, reviewer feedback, output acceptance, and release quality

## MVP capabilities

- Policy and claim document summarization
- Risk clause and coverage limit extraction
- Loss history comparison
- Missing document detection
- Question answering using retrieved document evidence
- Reviewer feedback, corrections, and approval workflow

## Product safeguards

- Every important answer should show its source document reference
- The system should clearly identify missing, unreadable, or conflicting information
- Users can edit, reject, or approve AI output
- Sensitive information is protected through role based access and data masking
- AI output supports human decisions; it does not make underwriting decisions independently

## Success measures

| Metric | Why it matters |
| --- | --- |
| Evidence backed answer rate | Checks whether important answers are supported by source documents |
| Reviewer edit rate | Shows where output needs improvement |
| Review time | Measures time saved without compromising quality |
| Critical error count | Tracks unsupported or incorrect outputs needing investigation |
| Feature adoption | Shows whether users find the workflow useful |

## Technology context

`Amazon Bedrock` · `Amazon Textract` · `Amazon S3` · `SQL` · `Postman` · `Jira` · `Confluence` · `Figma`

> This is a portfolio case study based on the type of AI product work I have delivered. It contains no client data, proprietary code, or confidential documents.
