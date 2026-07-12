# Evidence

## 2026-07-11

- Local inventory: the project contains one persona source file and no package/build/test configuration.
- Static content check: `수다글_페르소나_20명.md` is UTF-8, has 20 unique IDs (`P01`–`P20`), 2,743 characters, and contains no URLs or email addresses.
- Chrome Profile 1 read-only review: Naver Cafe `수다떨기` menu pages 1 and 2 were opened. A 59-post non-pinned sample was extracted from the visible list.
- Pattern result: 44 of 59 sampled posts had comments; overall averages were 48.1 views and 2.8 comments. Beginner and event-oriented titles were above the sample average.
- Limitation: the selected article detail surface did not render body text in the accessible page state, so body-style claims were not made.
- Title-pool validation: 30 local-only discussion-post titles were created across all 20 personas. Initial review marked 24 as pass and 6 as revise; all six were revised and the final pool has 30 pass titles. No title contains an unverified schedule, location, product claim, or health claim.
- Persona refinement: P01, P04, and P16 were designated as intentional `피클볼` keyword personas. Their titles and future bodies use the keyword once each; the remaining 17 personas do not force keyword use.
- Title pool 02: 30 additional local-only titles were generated across all 20 personas. P01/P04/P16 have six keyword-once titles; the remaining titles preserve situation-first phrasing.
- Title-length rule: future discussion-board titles must be 9~30 characters including spaces and punctuation. The 30 titles in pool 02 were verified at 20~30 characters.
- Title pool 03: 30 additional titles were produced under the 9~30-character rule, with P01/P04/P16 keyword use limited to one occurrence in six titles.
- Persona-system revision: all 20 personas now have an operational title-length band, opening frame, scene focus, ending/question rule, and batch-level variety constraints. Future generation must validate those fields before output.

## 2026-07-12

- `python C:\Users\dlatj\.codex\skills\goal-harness\scripts\harness-check.py --harness .goal-harness` completed with validation level 0 and reported no known project checks. This is expected because the project has no package manifest, executable script, lint, test, or build configuration.
- Static inventory found 18 files: 20-persona source, pattern analysis, title queue and review, four title-pool Markdown files, CSV title pools 02~04, and harness records.
- CSV validation: pools 02, 03, and 04 each contain 30 rows with unique IDs and no within-pool exact duplicate title. Across all three CSVs there are no exact duplicate titles.
- CSV/Markdown parity: pools 03 and 04 match. Pool 02 differs at rows 4 (comma after `느낌`) and 16 (comma after `순서`).
- Similarity review found a 0.85 character similarity between pool 02 row 22 (`피클볼 패들 무게가 다르게 느껴지는 날도 있나요?`) and pool 03 row 22 (`피클볼 패들 면이 넓게 느껴지는 날도 있나요?`).
- Rule review found competing title ranges: 18~34 characters in the pattern analysis versus 9~30 characters in the persona source and later evidence. Pool 04 conforms to 9~30; pool 02 Markdown row 4 is 31 characters because of its extra comma.
- Full report: `docs/프로젝트_검토_2026-07-12.md`.
- Editorial decision: the canonical title-length rule is 9~34 characters, including spaces and punctuation. The persona source and pattern-analysis rule were updated; all existing title-pool ranges remain within this rule.

## Harness Check 2026-07-12T08:57:35+09:00

Level: 0

| Command | Result | Notes |
|---|---|---|
| `harness-check.py` | SKIP | no known project checks detected |
