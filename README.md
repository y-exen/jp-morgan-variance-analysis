# JPMorgan Chase: Quarterly Variance Analysis

An Excel model comparing JPMorgan Chase's last 6 quarters of reported
results against the same quarters a year earlier, with commentary on the
largest variances.

## Objective
Practise the core work of a Finance & Business Management role: track
results against a benchmark, explain variances for business partners,
and look ahead.

## Scope
- Company: JPMorgan Chase & Co.
- Period: Q2 2025 to Q3 2026
- Basis: managed basis (revenue lines)
- Benchmark: prior-year quarter (guidance-based budget to be added)
- Lines: net interest income, noninterest revenue, total net revenue,
  noninterest expense, pre-provision profit, provision for credit
  losses, net income
- Materiality threshold: variances over 15% flagged

## Model structure
| Tab | Purpose |
|---|---|
| Inputs_Actuals | Typed data from earnings supplements (blue) and formulas (black) |
| Variance | Absolute variance, % variance and Fav/Adv label |
| Top_Variances | Ranked list of material variances |
| Commentary | Drivers, one-off vs ongoing, recommended actions |

## Method notes
- Inputs are only typed on the Inputs tabs; everything else is formulas.
- Costs are stored as positive numbers; a rise in a cost is adverse.
- Variance % = (Actual - Prior year) / Prior year.

## Status
- [x] Data collection
- [x] Variance calculations
- [x] Material variances identified
- [ ] Commentary
- [ ] Guidance-based budget
- [ ] Rolling forecast with scenarios

## Sources
Company earnings releases and supplements from JPMorgan Chase investor
relations (links in `sources/source_links.md`).
