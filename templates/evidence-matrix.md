# Evidence matrix

One row per piece of evidence. Fill it the same day the evidence is collected. A spreadsheet version is in [evidence-matrix.csv](evidence-matrix.csv).

| Field | Description | Example |
|---|---|---|
| ID | Unique reference | EV-042 |
| Date | When it was collected | 2026-09-18 |
| Source type | Document · Tool data · Interview · Workshop · Observation | Workshop |
| Source reference | Document name, interviewee role (never name), or session | Test management workshop, activity 1 |
| Area | TMMi process area or TPI NEXT key area | Defect management |
| Observation | What was seen or said, as facts | Defect priority is changed by the developer without notifying the tester |
| Practice / checkpoint | Which practice or checkpoint it relates to | Defect priority agreed between roles |
| Effect | Supports · Contradicts · Neutral | Contradicts |
| Confidence | High · Medium · Low | Medium |
| Assessor | Who recorded it | CA |
| Notes | Follow-up question, cross-check pending | Confirm with defect tool export |

## Rating rules

- **Met:** at least two independent sources support it and none contradicts it.
- **Partially met:** support exists but is limited to some teams or projects.
- **Not met:** sources contradict it, or the practice is clearly absent.
- **Not assessed:** not enough evidence. Never rate unknown as met or not met.

## Good observations

| Weak | Strong |
|---|---|
| "Testing is chaotic" | "Three of four testers said test cases are written after development finishes" |
| "Bad metrics" | "The weekly report has 14 indicators; none was mentioned when asked which data supported the last release decision" |
| "Managers don't care" | "No business representative attends the release go/no-go meeting (observed twice)" |
