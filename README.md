# Sales Dashboard Audit â€” DSN AI Bootcamp 2026 (Data Analytics track)

**Tools:** Excel (data cleaning, PivotTables, dashboard)  
**Dataset:** 420 retail sales transactions (product, state, quantity, price, cost)

![Corrected dashboard](dashboard.png)

## The task
Management shared a sales dashboard and 8 claims about business performance.
My job: audit the data, fix the dashboard, and confirm or reject each claim with evidence.

## What I found
- **12 exact duplicate rows** (432 â†’ 420 transactions after removal).
- **31 missing cost values**, which made profit look higher than it was.
- **22 transactions (5.1%)** where reported revenue â‰  Units Ã— Unit Price Ã— (1 âˆ’ Discount).
- Inconsistent state/category labels (e.g. "Lagos", "Lagos ", "LAGOS") that split one market into three.
- Corrected revenue: **â‚¦46,679,725** Â· Corrected profit: **â‚¦14,590,425** (originally â‚¦16,617,270 â€” overstated by ~â‚¦2.0M).
- Result: all 8 management claims failed the audit (6 incorrect, 2 misleading) â€” including "Lagos is underperforming" (it was actually the most profitable state, â‚¦4.58M).

## What I did
1. Removed duplicate rows and filled/flagged missing cost values.
2. Recomputed revenue and profit from source columns instead of trusting the pasted totals.
3. Rebuilt the dashboard: KPI cards, revenue by product & state, profit margin, trend.
4. Tested all 8 management claims against the cleaned data â€” verdicts and evidence are in the report.

## Files
- [MercyIjegbai_DataAnalytics_FinalProject.xlsx](MercyIjegbai_DataAnalytics_FinalProject.xlsx) â€” cleaned data + dashboard
- [dashboard.png](dashboard.png) â€” dashboard snapshot
- [report.pdf](report.pdf) â€” written audit report with claim-by-claim verdicts

## What I learned
Never trust a dashboard's totals until you've recomputed them from the raw rows.
