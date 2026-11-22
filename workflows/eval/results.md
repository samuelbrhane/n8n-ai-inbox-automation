# Sorting evaluation

Run on 2026-11-22 with gpt-5.4-mini, using the same prompt and schema as the live workflow.

| Metric | Result |
|---|---|
| Category accuracy | 20/20 (100%) |
| Urgency accuracy | 20/20 (100%) |
| Emergencies caught | 3/3 |

Test set: 20 labelled emails in `test-emails.csv`. 6 questions, 5 repairs (3 emergencies), 3 complaints, 3 viewing requests and 3 spam emails, including two in Italian and one question the documents do not cover.

Run it again with workflow `5. Evaluate sorting` after changing the prompt.