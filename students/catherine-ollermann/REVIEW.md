# Catherine Ollermann — portfolio feedback and rubric review

The portfolio now explains Catherine's engineering background, junior machine learning engineer goal, and project evidence. Reviewers can reach all three project repositories directly from their cards and assess the sentiment result with its evaluation context.

All changed files are inside `students/catherine-ollermann/`. This PR includes the uncommitted improvements already present when this run began, as well as this run's feedback ledger, quote addition, unused-image removal, and responsive ordering change.

## Every change and its rubric item

| Change | Rubric item |
| --- | --- |
| Preserve the original introduction and add AI studies, energy focus, and the junior machine learning engineer goal. | 1 — Who you are; 2 — A repeatable sentence |
| Add “I build Python tools to compare energy trends and evaluate machine learning models.” to the existing quote. | 2 — A repeatable sentence; 6 — Answer every comment |
| On screens at most 860px wide, place the main content before the photo/link sidebar using page-local CSS. Desktop ordering is preserved. | 1 — Who you are without scrolling; visual verification remains incomplete |
| Replace the generic energy description with the comparison question, bundled energy_sample.csv data, CSV uploads, and interactive features. | 3 — Work with an outcome; 6 — Answer every comment |
| Explain linear regression projections and the documented temporal-validation limitation. | 3 — Work with an outcome; 6 — Answer every comment |
| Add the live demo link directly to the energy card and add its repository link. | 4 — Links work for logged-out visitors; 6 — Answer every comment |
| Explain how to wake the sleeping Streamlit demo without promising a fixed startup time. | 4 — Links work for logged-out visitors; 6 — Answer every comment |
| Replace the generic AWS description with its EIA SEDS source, S3/PySpark/DynamoDB workflow, state/year storage keys, Plotly outputs, and documented model comparison, with a forecasting caveat. | 3 — Work with an outcome; 6 — Answer every comment |
| Add a direct AWS code/results repository link. | 4 — Links work for logged-out visitors; 6 — Answer every comment |
| Replace the brief sentiment description with its text pipeline, averaged embeddings, 5,000 training reviews, 1,000 held-out test reviews, and seed. | 3 — Work with an outcome; 6 — Answer every comment |
| Contextualize 79% accuracy with 77.56% F1 and a calculated 51.2% always-negative comparison; explicitly state that a TF-IDF/logistic-regression comparison is not documented. | 3 — Work with an outcome; 6 — Answer every comment |
| Explain the sentiment model's 200-token limit, loss of word order, and documented future evaluation improvements. | 3 — Work with an outcome; 6 — Answer every comment |
| Add a direct sentiment code/evaluation repository link. | 4 — Links work for logged-out visitors; 6 — Answer every comment |
| Remove aws-energy-pipeline.png, customer-sentiment-intelligence.png, and energy-intelligence-platform.PNG after announcing the removal; preserve the referenced JPGs. | 6 — Answer every comment, including unused-image feedback |
| Add LEDGER.md with all three feedback comments verbatim, final statuses, and before/after evidence. | 6 — Answer every comment |
| Add student-folder CONTEXT.md and this REVIEW.md to document evidence, checks, pass history, and limits. | 1–6 — Review evidence and honest reporting; 6 — Feedback accountability |

## Final rubric scores

| Item | Result | Evidence |
| --- | --- | --- |
| 1 — Who you are, without scrolling | **Fail** | The page says “Catherine Ollermann” and “I'm a Petroleum Engineer exploring how AI can solve real-world challenges.”, but the revised page's above-the-fold layout has not been verified in a browser. |
| 2 — One sentence a reader could repeat | **Pass** | The page says “I build Python tools to compare energy trends and evaluate machine learning models.”, a concrete description tied to the displayed projects. |
| 3 — Something you actually made, with an outcome | **Pass** | The page describes an app “to compare states, filter energy indicators and years, and explore a U.S. map”, a pipeline that “moves data through Amazon S3, PySpark cleaning and aggregation, and DynamoDB storage”, and sentiment “79% accuracy and 77.56% F1.” |
| 4 — Every link works for a stranger who is logged out | **Fail** | The page includes “CV”, “MS in AI”, and “View sentiment code and evaluation”, but every link has not been clicked from the revised page in a private window; this is incomplete verification, not evidence that those targets are broken. |
| 5 — Nothing unfinished is visible | **Pass** | The title is “Catherine Ollermann — MS in Artificial Intelligence”, the portrait alt text is “Photograph of Catherine Ollermann”, and source review found no placeholder text, duplicate paragraphs, empty headings, or inconsistent name. |
| 6 — Every comment got an answer | **Pass** | 3 comments, 3 verbatim rows: 3 Fixed, 0 Declined, 0 Needs you; each row includes before/after evidence present in the page. |

## Pass history and stopping decision

- Baseline: items 2, 3, and 5 passed; items 1 and 4 lacked the required browser verification; item 6 failed because LEDGER.md was missing.
- Pass 1: added the energy/AI quote sentence, removed unused PNG originals, and created the complete ledger; item 6 changed from fail to pass.
- Pass 2: moved the main content before the sidebar on narrow screens. Source verification confirmed the CSS change, but browser policy still prevented local-file preview, so item 1 could not be marked pass. No failing item turned into a pass.
- Stopped after 2 passes under AGENT.md's no-progress rule, within its five-pass limit. Items 1 and 4 still fail verification. No further improvement passes were run.

## Validation and limits

- Checked that three feedback comments match three ledger rows verbatim, and all rows end Fixed.
- Checked quoted after-evidence against HTML-decoded page text.
- Checked the four displayed images and local resume.pdf exist, and all four project destinations are present in the HTML.
- Confirmed the three unused PNG originals are gone and the displayed JPGs remain.
- Earlier in this chat, public project repositories and the sentiment notebook were inspected logged out, and the Streamlit demo loaded after its normal wake-up action. Those checks do not replace the rubric's current-page private-window test.
- LinkedIn uses the author's `/in/catherine-ollermann` profile address. A logged-out sign-in wall, if encountered, is exempt under the rubric; it was not re-tested in this run.
- The updated local layout has not been visually verified. Browser policy previously rejected the file URL; no alternate browser route was used to bypass that restriction.
- No model retraining, new accuracy measurement, or TF-IDF baseline experiment was performed. The AWS details were checked against its project README, not a pipeline rerun.
- Shared files, RUBRIC.md, and other students' folders were not modified. Nothing was pushed to main.
