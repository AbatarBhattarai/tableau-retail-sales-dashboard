# Retail Sales Dashboard — Tableau

I built this dashboard in Tableau using the same 1,200-order retail
dataset as my Power BI dashboard, so I could show the same analysis in
both tools recruiters ask for.

## What it shows

- **Total revenue:** $118,568.75 across 1,200 orders (Jan–Dec 2024)
- **Average order value:** $98.81
- **Top category:** Clothing — $37,046.85, 31.2% of revenue
- **Top region:** West — $30,138.80
- **Peak month:** November 2024 — $14,948.60, up 73.2% on October
- **Slowest month:** May 2024 — $7,335.45
- **Channel split:** In-Store $59,286.50 vs Online $59,282.25 — almost even

## How I built it

- Connected Tableau to the cleaned CSV (`retail_orders_clean.csv`)
- Calculated fields for Total Revenue, Total Orders, Average Order Value
  and Month
- Table calculations for month-over-month revenue change and each
  category's share of total revenue
- Five sheets (KPI summary, category, region, monthly trend, channel)
  combined into one 1280 × 720 dashboard

## Files

- `retail-sales-dashboard.twb` — the Tableau workbook (opens in Tableau
  Desktop or Tableau Public; keep it next to the CSV, it reads data from
  there)
- `retail_orders_clean.csv` — the cleaned dataset (1,200 orders, Jan–Dec
  2024, synthetic practice data)
- `calculated-fields.txt` — every formula used, in one place

## Live dashboard

[Tableau Public link — add after publishing]

## Skills used

Tableau (calculated fields, table calculations, dashboards) · Python
(pandas, for cleaning) · SQL · Data visualization
