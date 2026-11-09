# Superstore Sales Dashboard

A single-page Power BI report for sales performance analysis of Superstore data. It shows overall results, how sales split by customer segment, product sub-category and geography, and how sales trend over time.

## Dashboard at a Glance

| KPI | Value |
|---|---|
| Sum of Sales | 2.33M |
| Sum of Profit | 292.30K |
| Sum of Quantity | 39K |
| Sum of Discount | 1.58K |

Overall profit margin is about 12.5% (292.30K / 2.33M).

## Visuals

| Visual | Type | What it shows |
|---|---|---|
| Sales by Segment | Pie | Consumer 1.17M (50.32%), Corporate 0.72M (30.77%), Home Office 0.44M (18.92%) |
| Sales by Year | Line | 2023 to 2026. Roughly flat to slightly down in 2024 (~0.5M), then rising to ~0.75M by 2026 |
| Sales by Sub-Category | Funnel | Ranked from Chairs and Phones at the top down to Fasteners (8.53K, ~2.5% of the top value). Storage is 224.64K; Accessories 167.38K; Bookcases 115.36K; Furnishings 95.60K; Supplies 46.73K; Envelopes 16.53K |
| Sales by State/Province | Treemap | California and New York are the largest blocks, then Texas, Washington, Pennsylvania, Florida, Illinois, Ohio, Michigan, Virginia |
| KPI cards | Cards | Quantity, Discount, Sales, Profit |
| Total Sales | Donut | Total sales of 2.33M (100%) |

## Key Insights

- Consumer customers generate half of all sales; Home Office is the smallest segment (under 20%).
- Sales growth accelerates after 2024.
- Revenue is concentrated in a few states, led by California and New York.
- Chairs and Phones are the top sub-categories; Fasteners, Labels and Envelopes contribute the least.

## Requirements

- Power BI Desktop

## Usage

1. Open the report in Power BI Desktop.
2. Click any chart element (a segment, a state, a sub-category) to cross-filter the other visuals.
3. Use the Data pane to add fields or build extra visuals on the canvas.

## Notes

- Figures are as displayed on the dashboard (rounded).
- The second report page is an empty canvas, ready for additional visuals.
