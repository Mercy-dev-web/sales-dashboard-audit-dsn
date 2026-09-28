# Sales Dashboard Audit — DSN AI Bootcamp 2026 (Data Analytics track)

**Tools:** Excel (Power Query-free cleaning, PivotTables, dashboard)  
**Dataset:** 420 retail sales transactions (product, state, quantity, price, cost)

## The task
Management shared a sales dashboard and 8 claims about business performance.
My job: audit the data, fix the dashboard, and confirm or reject each claim with evidence.

## What I found
- Duplicate transactions and missing cost values were inflating profit.
- Several revenue figures did not match quantity × price.
- Corrected profit: **₦14,590,425** (dashboard originally showed ₦16,617,270 — overstated by ~₦2.0M).
- Corrected revenue: **₦46,679,725**.

## What I did
1. Removed duplicate rows and filled/flagged missing cost values.
2. Recomputed revenue and profit from source columns instead of trusting the pasted totals.
3. Rebuilt the dashboard: KPI cards, revenue by product & state, profit margin, trend.
4. Tested all 8 management claims against the cleaned data — verdicts and evidence are in the report.

## Files
- `MercyIjegbai_DataAnalytics_FinalProject.xlsx` — cleaned data + dashboard
- `dashboard.png` — dashboard snapshot
- `report.pdf` — written audit report with claim-by-claim verdicts

## What I learned
Never trust a dashboard's totals until you've recomputed them from the raw rows.
