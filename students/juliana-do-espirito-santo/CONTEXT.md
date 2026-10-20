# My page — status

## Who I am
- My computer: macOS
- My name: Juliana do Espírito Santo
- My GitHub username: jujusanto
- My fork: https://github.com/jujusanto/msai-portfolio
- My branch name: student/juliana-do-espirito-santo (one branch all term — never make a second one)
- My folder name: students/juliana-do-espirito-santo (inside msai-portfolio)
- On my laptop: /Users/julyl/Documents/my-page/msai-portfolio
  - "origin" = my fork (jujusanto), "upstream" = the class project (rodolfocapdevilla-au)

## My page as it is now (index.html)
- Tab title: "Juliana do Espírito Santo — MS in Artificial Intelligence"
- Top bar: badge "Juliana do Espírito Santo" · Projects · Education & Experience · All students · MS in AI
- Left rail:
  - Photo: photo.jpg (my headshot, 800 × 800, 126 KB)
  - Buttons:
    1. LinkedIn profile → https://www.linkedin.com/in/juliana-do-espirito-santo-67005115a
    2. GitHub profile → https://github.com/jujusanto
    3. Résumé → resume.pdf (my own public CV, "…Final-2.pdf", 433 KB, 1 page, no phone number or address)
  - No fourth button (no address for it)
- Heading: "Juliana do Espírito Santo"
- My one line (quote): After more than ten years running the brand and marketing of an online store, I now study Artificial Intelligence at Atlantis University. My projects look at how AI can answer customers’ routine questions and show which people go on to become customers.
- Block "Current Projects" — 3 cards, three sentences each (what it is, what I did, what came out):
  1. "The Human-Centered AI Marketing System" — picture project-marketing-system.jpg (workbook cover from my flyer, 94 KB, no price). The framework PDF stays private.
  2. "Local AI Assistant for an Orthodontic Front Office" — picture project-local-assistant.svg. From "Final project 1.pdf" (a proposal; the assistant is not built yet).
  3. "What Drives Treatment Starts at an Orthodontic Practice (exploratory analysis)" — picture project-patient-conversion.svg (bar chart from my report). From "Project 2.pdf" (data preparation and charts on a simulated dataset I created; the model is the next phase). Says the link was measured by correlation (0.74 and 0.59).
- Block "Education & Experience" (from my CV, with dates):
  - Education: Master of Science in Artificial Intelligence, Atlantis University · 2025–2027 / Digital Marketing Certification, DMI & ESPM · 2024 / Bachelor's Degree in Publicity and Advertising, Pontifical Catholic University of Goiás · 2009
  - Experience: AI Marketing Specialist & Customer Service Assistant, Barbosa Orthodontics · May 2026–Aug 2026 / Brand Manager, E-commerce & Digital Marketing, Ju Santo Store · 2009–2023 / Volunteer, Cancer Hospital of Goiás · 2017–2020
- Other files in my folder: CONTEXT.md (this file), REPORT.md (one-page summary), FEEDBACK.md (raw feedback from my page, exactly as written), AGENT.md (instructions for the agent that improves my page), RUBRIC.md (16 pass/fail checks), GOAL.md (my reader and end state)

## Tonight (Wednesday 2026-09-30)
- Found my first pull request #63 was MERGED by my teacher
- Switched to main and pulled the latest class project into my fork and my laptop (no new clone)
- Switched back to my own branch and merged the latest main into it (no new branch)
- Added the accent to my name everywhere: Espírito
- Removed the empty fourth link button
- Replaced the 4 template cards with my 3 real projects, written in plain language, each with a picture
- Filled in Education & Experience from my CV, then removed Peter Coppola to match my new CV
- Rewrote my one line: starts with what I have done, no repeat of my name, no marketing words
- Privacy: my first CV showed my phone number, so it was never sent. My new CV (no phone, no city) is the only one on GitHub.
- Opened pull request #76, updated its description, and renamed it "Round two — Juliana do Espírito Santo":
  https://github.com/rodolfocapdevilla-au/msai-portfolio/pull/76
- Saves sent to #76:
  - 5959526 Fix links, project cards and education
  - a8f7208 Remove résumé to keep personal details private
  - 6b65958 Add project cards with pictures
  - cf1767d Add dates and volunteer role to education and experience
  - fdae4ac Add public CV and match experience to it
  - 2b96801 Update CONTEXT.md
  - abf2363 Rewrite my first line and update notes

## Monday (2026-09-28) — setup
- Wrote CLAUDE.md and CONTEXT.md
- Installed gh 2.101.0 (no Homebrew, no password) and signed in as jujusanto
- Forked the class project, cloned my fork, created my branch, copied _template into my folder
- Put my name, my one line, my photo, and my LinkedIn and GitHub links on the page
- Saved "Add Juliana do Espirito Santo page" and opened pull request #63 (now merged):
  https://github.com/rodolfocapdevilla-au/msai-portfolio/pull/63

## Questions still open
- Were my two orthodontic projects part of my internship, or course projects only? (Cards say "course" / "an orthodontic practice")
- Did I run the test of Llama 3.2 3B on my MacBook Air (about 45 tokens per second)? If yes, it can go on card 2.
- ANSWERED 2026-10-19: the 500-lead dataset in project 3 is a simulated dataset I created for the course (now said on the card)
- My Gmail address is on my public CV — OK to keep?

## My current pull request
- #76 "Round two — Juliana do Espírito Santo" — MERGED on 2026-10-01: https://github.com/rodolfocapdevilla-au/msai-portfolio/pull/76
- #88 "Update CONTEXT.md — Juliana do Espírito Santo" — MERGED on 2026-10-19: https://github.com/rodolfocapdevilla-au/msai-portfolio/pull/88
- #93 "Add FEEDBACK.md — Juliana do Espírito Santo" (FEEDBACK.md, AGENT.md, RUBRIC.md, card 3 changes) — MERGED: https://github.com/rodolfocapdevilla-au/msai-portfolio/pull/93
- #96 "Add GOAL.md — Juliana do Espírito Santo" (open, waiting for my teacher): https://github.com/rodolfocapdevilla-au/msai-portfolio/pull/96
- In my own fork: #1 "AGENT.md run: rubric pass, 2026-10-19" (open), from branch agent/rubric-pass-2026-10-19 into my branch. It adds "(private)" after the 31-page workbook on card 1: https://github.com/jujusanto/msai-portfolio/pull/1
- Rule: only one pull request open at a time. While it is open, keep pushing to it. A merged one never reopens — after my teacher merges, open the next one from the SAME branch.

## Thursday 2026-10-15
- Pulled the latest class project into my fork and my laptop (64 new saves, now at 7a6c681)
- Merged the latest main into my branch (no new branch, no conflicts)
- Opened pull request #88 with this CONTEXT.md update (same branch)
- Updated REPORT.md (Round two merged, #88, all saves) and sent it to #88

## Monday 2026-10-19
- Saved the raw feedback from my page in FEEDBACK.md, exactly as written
- Wrote AGENT.md: goal, what it may read and change (only my folder), what it may never do, and the loop
- Ran AGENT.md with FEEDBACK.md as the goal. Card 3 changes: new title "(exploratory analysis)", "An exploratory analysis of…", "simulated dataset … for the course", and "strongest correlation … (0.74 and 0.59)"
- Replaced the stopping rule ("Stop when the page is good." → stop when every item in RUBRIC.md passes, at most five passes) and added: never rewrite my sentences unless FEEDBACK.md quotes a problem
- Wrote RUBRIC.md (16 pass/fail checks)
- Ran AGENT.md against RUBRIC.md: 15 of 16 pass. Marked the workbook "(private)" on card 1 (fork pull request #1). Still failing: item 12, because card 2 mentions the proposal without a link or "private"
- Wrote GOAL.md: a marketing director at an orthodontic practice group whose leads don't start treatment; they message me on LinkedIn
- #88 and #93 were merged; opened #96 for GOAL.md (same branch, updated from the class project first)

## Next step
- Decide about card 2's proposal (private? public link? or accept item 12 as passed) so RUBRIC.md item 12 can pass
- Merge my fork's pull request #1 into my branch if I want the "(private)" change
- Wait for my teacher to merge #96. While it is open, keep pushing to it.
