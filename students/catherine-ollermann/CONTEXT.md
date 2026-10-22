# Portfolio page review — 2026-10-20

## Latest rubric run

- Branch: student/catherine-ollermann-rubric-20261020 on Catherine's fork.
- Read the root RUBRIC.md without changing it. See REVIEW.md for all six scores and the complete PR change-to-rubric mapping.
- Pass 1 turned item 6 from fail to pass: added the energy/AI quote sentence, removed the three unused project PNGs while retaining the JPGs, and created LEDGER.md with three verbatim comments and three Fixed responses supported by before/after evidence.
- Pass 2 reordered the main content before the sidebar at widths up to 860px. The browser block still prevents visual verification, so this pass produced no newly verified passing rubric item.
- Stopped after two passes under the no-progress rule. Items 1 and 4 still fail because their required browser checks remain incomplete; items 2, 3, 5, and 6 pass.
- Git works when run as Catherine's Windows user. The earlier repository-detection problem was an environment limitation, not proof that Git metadata was missing.
- Pull request: https://github.com/rodolfocapdevilla-au/msai-portfolio/pull/97, from this fork branch to the class repository's main branch. The earlier review below describes the state before this rubric run.

## Earlier review

Only Catherine's student folder was changed. No commit, push, or pull request was made.

## Current changes

- Preserved the original introduction and added AI studies, project focus, and the junior machine learning engineer goal.
- Replaced the three generic project descriptions with details verified against Catherine's public project repositories.
- Added direct repository links for all three projects and retained the energy application's live demo link.
- Identified the energy application's bundled energy_sample.csv dataset, interactive comparison features, linear regression projection, and forecasting limitation.
- Added a demo wake-up note after observing the sleeping app and successfully waking it through its normal public interface.
- Identified the AWS pipeline's EIA SEDS dataset, processing and storage stages, and documented model comparison without claiming validated future forecasting performance.
- Identified the sentiment model's averaged embeddings, training/test sampling, held-out accuracy and F1, and limitations. The 51.2% always-negative comparison is calculated from the notebook's 512 negative labels among 1,000 test reviews; it is not a separately trained baseline. No TF-IDF/logistic-regression comparison was found in the reviewed notebook.
- Original PNG images remain; the page references the optimized JPG files.

## Evidence reviewed

- https://github.com/catherineollermann-dot/energy-intelligence-platform — README and app.py.
- https://energy-intelligence-platform-project.streamlit.app/ — successfully loaded with its demo dataset after wake-up.
- https://github.com/catherineollermann-dot/Cloud-Based-Energy-Analytics-Pipeline-on-AWS — README, including the SEDS data source, DynamoDB keys, and model comparison.
- https://github.com/catherineollermann-dot/customer-sentiment-intelligence — README and notebooks/v1 - Professional notebook completed (2).ipynb.

## Verification and remaining limits

- File checks passed for three project cards, four project destinations, four local images with alt text, the local CV, and the preserved original introduction.
- Browser policy blocked the local file preview. The updated page has not been visually verified; do not describe visual review as complete.
- The AWS model details were checked against its README, not a rerun of the pipeline. No models were retrained or reevaluated.
- The available msai-portfolio folder was not recognized as a Git repository by the earlier read-only diff check. Do not claim a clean Git diff or upload readiness without verifying repository state.
- Additional model experiments belong to the project repositories and are outside the authorized portfolio-folder scope.
- No other student's folder or RUBRIC.md was read or changed during this continuation.

## Ledger-first run — 2026-10-21

- PR #97 was merged before this run. New branch: student/catherine-ollermann-ledger-20261021.
- Created the required numbered root LEDGER.md first, then synchronized the student-folder ledger to it. All three original comments are word for word: two Fixed, one Declined for the conflict with the author's later instruction to retain deeper implementation detail in the repository. No comments are open. A decline is not credited as an improvement pass.
- Corrected the ledger's stale sentiment quotations while preserving the approved portfolio HTML unchanged. See REVIEW-2026-10-21.md for the ledger-first description, full check scores, scope, and evidence.
- Verified current local HTML matches upstream main. Browser review of the deployed page at 1280×720 confirmed name and meaningful role above the fold; all four displayed images loaded.
- Stopped after one pass because all comments are answered and five of six checks pass. Check 4 remains failed/unverified: no complete confirmed-private-window link test was performed. Checks 1, 2, 3, 5, and 6 pass.
- New PR: https://github.com/rodolfocapdevilla-au/msai-portfolio/pull/101, with the ledger at the start of its description; no page content, protected root instructions, shared files, or other students' folders changed.
