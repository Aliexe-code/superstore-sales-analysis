# Superstore Sales Analysis — Project Summary

**By:** Eman Mahmoud Ahmed Ali Omar  
**Mentor:** Ali Mohamed — Gulf Plastics Industries (GPI)  
**Date:** September 2026  

---

## What is this about?

I analyzed **9,994 orders** from a large US retail company spanning **4 years (2014–2017)**. The dataset includes what products were sold, how much they cost, what discounts were given, and how much profit was made.

**The big question:** Where is the money actually being made? Because high sales don't always mean high profit.

---

## What did I do?

I asked **3 business questions** and answered each with data and charts:

### 1. Which products make the most money?

| Product Category | Sales | Profit | Profit Margin |
|----------------|-------|--------|---------------|
| Technology | $836K (36%) | **$145K (51%)** | **17.4%** ✅ |
| Office Supplies | $719K (31%) | $122K (43%) | 17.0% ✅ |
| Furniture | $742K (32%) | $18K (6%) | **2.5%** ⚠️ |

**Key insight:** Furniture brings in a lot of revenue but almost no profit. It's a revenue trap — the company is essentially giving away Furniture products. Technology is the real profit engine.

---

### 2. Are sales growing over time?

- **2014:** $484K → **2017:** $733K = **51.4% growth**
- Every year has a **Q4 (holiday) spike** — Q4 2017 hit $280K
- Profit grew even faster than sales: **88.7%**

**Key insight:** The business is healthy and growing. Holiday seasons are critical — they should plan inventory and staffing around Q4.

---

### 3. Do discounts help or hurt profit?

| Discount Level | Avg Profit per Order |
|---------------|---------------------|
| 0% discount | **+$67** ✅ |
| 0–20% discount | +$27 ✅ |
| 20–40% discount | **-$78** ❌ |
| 40%+ discount | **-$107** ❌ |

Correlation: **r = -0.22** (more discount = less profit)

**Key insight:** Deep discounts (above 20%) destroy profit. The company should cap discounts at 20% or tie them to product margins.

---

## What should the business do?

1. **Re-think Furniture strategy** — either raise prices, cut costs, or reduce discounting on Furniture
2. **Cap discounts at 20%** — beyond that, every sale loses money
3. **Plan for Q4** — holiday season drives nearly half of annual revenue
4. **Focus on Technology and Office Supplies** — these are the real profit drivers

---

## What's in this repo?

- **`Superstore_Analysis.ipynb`** — The full analysis notebook (runs from start to finish)
- **`findings.md`** — Detailed findings with charts
- **`walkthrough_script.md`** — My 2-minute presentation script for you
- **`images/`** — 6 charts showing all the findings visually
- **`data/superstore_clean.csv`** — The cleaned dataset used in the analysis

---

## One thing I couldn't check

The dataset only covers 2014–2017, so I can't say if these trends will continue. Also, the data doesn't include costs like shipping and manufacturing, so I can only measure gross profit — not the true net profit per product.

---

**All analysis is reproducible** — anyone who clones this repo can run the notebook and get the same results.

---

*Questions? Check the GitHub repo or ask me directly.*
