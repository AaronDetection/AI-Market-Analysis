# The True Cost of AI Talent — Market Analysis 2025

A data analysis of the global AI job market focused on salary premiums, compensation structures by company size, and demand-vs-salary dynamics over time. Built in Python and visualized in Power BI.

---

## What this project answers

Three business questions that go beyond "which skills pay more":

1. **Skill salary premium (%)** — by how much does each skill beat the market median, and which combinations compound that premium?
2. **Company size sweet spot** — is there a segment where salary AND benefits score are both above average?
3. **Demand vs. salary over time** — does posting volume actually correlate with salary growth, or do they decouple?

---

## Stack

- **Language:** Python (Pandas, Matplotlib, Seaborn)
- **Visualization:** Power BI (dual-axis charts, scatter plots, bar charts)
- **Dataset:** Global AI Job Market & Salary Trends 2025 — Kaggle (bismasajjad)

---

## Key findings

| Finding | What it means |
|---|---|
| Git + NLP lead salary premiums | Senior role signal — not just tool popularity |
| Tableau sits below median | Pure BI skills approaching commodity without engineering layer |
| Medium companies = best total package | Salary + benefits score combined beats large companies |
| Salary spikes in low-volume months | Scarcity pricing for niche senior profiles |

---

## Why the framing matters

The questions were written from a CFO/HR perspective, not a candidate perspective. The salary premium analysis directly inputs into an upskilling vs. hiring decision. That framing — treating labor market data as a business intelligence problem — is what differentiates this from a standard EDA project.

---

## Files

```
├── analysis/
│   ├── q1_skill_premium.py
│   ├── q2_company_compensation.py
│   └── q3_demand_vs_salary.py
├── dashboard/
│   └── AI_Market_2025.pbix
└── data/
    └── ai_job_market_2025.csv
```
