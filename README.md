# Retail Sales Dashboard — Tableau

By Abatar Bhattarai

## Business question

Do the retail sales results hold up the same way in Tableau as they did in Power BI — and can the same story be told in both tools recruiters ask for?

## Data

The same 1,200-order retail dataset (Jan–Dec 2024, synthetic practice data) as my Power BI dashboard, from my Retail Sales Analysis project.

## What I did

- Connected Tableau to the cleaned CSV (`retail_orders_clean.csv`)
- Wrote calculated fields for Total Revenue, Total Orders, Average Order Value, and Month
- Used table calculations for month-over-month revenue change and each category's share of total revenue
- Built five sheets (KPI summary, category, region, monthly trend, channel) and combined them into one 1280 × 720 dashboard
- Published the dashboard to Tableau Public

## Key finding

The Tableau build reproduces the same verified numbers: **total revenue $118,568.75 across 1,200 orders**, average order value **$98.81**, Clothing the top category at **$37,046.85 (31.2% of revenue)**, the West the top region at $30,138.80, and a peak month of **November 2024 — $14,948.60, up 73.2% on October**, with in-store and online revenue almost even ($59,286.50 vs $59,282.25).

## Recommendation

The finding for a business reader is the same one the numbers keep giving: Clothing and the November peak drive the year, so that is where stock and promotion planning should concentrate — and this dashboard puts that pattern on one page that anyone can open from the Tableau Public link below.

**Live dashboard:** [Retail Sales Dashboard — 2024 on Tableau Public](https://public.tableau.com/app/profile/abatar.bhattarai/viz/RetailSalesDashboard2024_17946829544680/RetailSalesDashboard)

---

I built this dashboard in Tableau using the same 1,200-order retail dataset as my Power BI dashboard, so I could show the same analysis in both tools recruiters ask for.

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
- Calculated fields for Total Revenue, Total Orders, Average Order Value and Month
- Table calculations for month-over-month revenue change and each category's share of total revenue
- Five sheets (KPI summary, category, region, monthly trend, channel) combined into one 1280 × 720 dashboard

## Files

- `retail-sales-dashboard.twb` — the Tableau workbook (opens in Tableau Desktop or Tableau Public; keep it next to the CSV, it reads data from there)
- `retail_orders_clean.csv` — the cleaned dataset (1,200 orders, Jan–Dec 2024, synthetic practice data)
- `calculated-fields.txt` — every formula used, in one place

## Live dashboard

[Retail Sales Dashboard — 2024 on Tableau Public](https://public.tableau.com/app/profile/abatar.bhattarai/viz/RetailSalesDashboard2024_17946829544680/RetailSalesDashboard)

## Skills used

Tableau (calculated fields, table calculations, dashboards) · Python (pandas, for cleaning) · SQL · Data visualization
