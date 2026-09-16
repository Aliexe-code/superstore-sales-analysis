# Task Board — Superstore Sales Analysis (Days 16-18)

> For Ali (mentor) to create as GitHub Issues + Milestones. For Eman: this is your day-by-day checklist. Close an issue only when its **Definition of Done** is met and pushed to GitHub.

## How to Create on GitHub (Ali, 5 minutes)

1. On https://github.com/emanomar2006git/superstore-sales-analysis → Issues → Milestones → New Milestone: `Day 16 — Clean + EDA + 2 Qs`, `Day 17 — Finish + Findings + README`, `Day 18 — Polish + Walkthrough`
2. For each Issue below: Issues → New Issue → paste Title + Body → assign to `emanomar2006git` → add to Milestone → Create
3. Eman moves cards: To Do → In Progress → Done by closing the Issue with a commit message like `Closes #3`

---

### Milestone: Day 16 — Clean, Explore, and First Draft (Goal: 2 of 3 Qs answered)

#### Issue #1: Complete cleaning notebook `notebooks/02_cleaning.ipynb`
**Labels:** `Day 16`, `cleaning`
**Body:**
- [ ] All 6 cleaning steps have code + markdown explanation
- [ ] Dates parsed, whitespace stripped, duplicates checked, numeric types verified
- [ ] `data/superstore_clean.csv` generated and committed
- [ ] Cleaning summary bullets added at bottom of notebook

**Definition of Done:** `data/superstore_clean.csv` exists in repo, notebook runs, and every cleaning step has a comment/markdown (checklist items 7-10).

#### Issue #2: Complete EDA notebook `notebooks/03_eda_exploration.ipynb`
**Labels:** `Day 16`, `eda`
**Body:**
- [ ] Distributions of Sales/Profit/Discount (histogram + describe)
- [ ] Top categories/sub-categories (bar)
- [ ] Sales/profit over time (line, monthly)
- [ ] Outliers via boxplot + IQR
- [ ] Correlation Discount vs Profit
- [ ] EDA Summary bullets at bottom

**Definition of Done:** Notebook runs, all 5 EDA blocks have a chart or table, summary bullets written.

#### Issue #3: Build Q1 and Q2 in `Superstore_Analysis.ipynb` (Main Notebook)
**Labels:** `Day 16`, `analysis`, `Checkpoint 3`
**Body:**
- [ ] Section 4 (Q1): compute + bar chart + `images/question1_revenue_by_category.png` + 3-sentence Interpretation
- [ ] Section 5 (Q2): compute + line chart + `images/question2_sales_over_time.png` + 3-sentence Interpretation
- [ ] Descriptive stats (mean/median/std) included where relevant
- [ ] At least 2 different chart types used

**Definition of Done:** Main notebook has 2 fully answered questions, each with number + chart with title/labels + Interpretation. Ready for Checkpoint 3 review.

---

### Milestone: Day 17 — Complete Analysis, Findings, README

#### Issue #4: Complete Q3 + Additional Analysis in `Superstore_Analysis.ipynb`
**Labels:** `Day 17`, `analysis`
**Body:**
- [ ] Section 6 (Q3): correlation + scatter plot + `images/question3_discount_vs_profit.png` + 3-sentence Interpretation
- [ ] Section 7 (Additional): at least one of: IQR outlier check, segment boxplot, or SQL query on DataFrame
- [ ] At least 3 different chart types across Q1-Q3 (e.g., bar, line, scatter)

**Definition of Done:** All 3 Analysis Questions answered, each with appropriate visualization and Interpretation (checklist items 11-16).

#### Issue #5: Write Findings (`findings.md` + Section 8 in notebook)
**Labels:** `Day 17`, `writing`
**Body:**
- [ ] 5–8 findings, each with a specific number and supporting chart reference
- [ ] Findings match notebook outputs (re-read numbers!)
- [ ] Findings in plain English (non-technical reader can trust them)
- [ ] Copy findings into `findings.md` and into Section 8 of `Superstore_Analysis.ipynb` (keep in sync)

**Definition of Done:** `findings.md` exists, 5–8 specific findings, consistent with notebook (checklist items 17-22).

#### Issue #6: Write README + export charts
**Labels:** `Day 17`, `writing`
**Body:**
- [ ] Replace all TODOs in `README.md` (objective, dataset link, tools, findings bullets, limitations)
- [ ] At least one PNG in `images/` and embedded in README with `![alt](images/...)`
- [ ] Repository Structure section matches actual repo
- [ ] How to Run steps are copy-paste runnable

**Definition of Done:** README renders correctly on GitHub with working image, dataset link, tools, and findings summary (checklist items 23-31). Mentor does informal Day 17 review.

---

### Milestone: Day 18 — Polish, Push, Present

#### Issue #7: Re-run and polish (reproducibility)
**Labels:** `Day 18`, `polish`
**Body:**
- [ ] `Superstore_Analysis.ipynb`: Kernel → Restart & Run All in a fresh environment — no errors
- [ ] All imports at top, no hardcoded absolute paths (use `data/...` and `images/...`)
- [ ] Self-review against `Final_Project_Checklist.md` (36 items) — tick every box
- [ ] Fix any unchecked items immediately (simplify if needed, don't skip)

**Definition of Done:** Notebook runs top-to-bottom on fresh clone without errors (checklist items 3-5). Ready for final push.

#### Issue #8: Push + rehearse walkthrough
**Labels:** `Day 18`, `walkthrough`, `Checkpoint 4`
**Body:**
- [ ] `git add . && git commit -m "Final polish and walkthrough script" && git push`
- [ ] Verify README images render on GitHub, repo is Public
- [ ] Complete `walkthrough_script.md` with your 3 findings + one Limitation
- [ ] Rehearse out loud, timed, at least twice — target 1:45–2:15
- [ ] Deliver walkthrough to mentor (Checkpoint 4, pass/fail)

**Definition of Done:** Final push done, repo public, walkthrough script exists, verbal walkthrough delivered within time with specific numbers and one Limitation (checklist items 32-36).

---

## Suggested Commit Messages (use these so history is clear)

1. `Add question document and raw data inspection` ← already done (Eman)
2. `Add cleaning notebook and cleaned data` ← Issue #1
3. `Add EDA exploration` ← Issue #2
4. `Add main analysis notebook with Q1 and Q2` ← Issue #3
5. `Complete main analysis notebook` ← Issue #4
6. `Add findings, README, and exported charts` ← Issues #5-6
7. `Final polish and walkthrough script` ← Issues #7-8

## Mentor Checkpoints

- **Checkpoint 3 (End of Day 16):** Review Issues #1-3. Are cleaning documented? Are 2 Qs answered with charts + Interpretations? Are findings so far grounded in numbers?
- **Checkpoint 4 (End of Day 18):** Grade against `Final_Project_Checklist.md` (36 items). Record Pass/Fail with unmet items listed if Fail.
