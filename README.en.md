# Xbox Game Pass Dashboard (Executive Sales Dashboard)

Professional sales dashboard built in **Excel**, designed to turn raw data into clear, useful visual information for performance analysis and data-driven decision-making.

The model simulates the commercial operation of **Xbox Game Pass** (Core, Standard, and Ultimate plans, add-ons, and billing cycles) and lets you simulate scenarios by changing only the business parameters.

## File

- `Dashboard_Xbox_Professional.xlsx` — main file with the completed dashboard.

## Workbook Structure

The file consists of 5 sheets:

| Sheet | Description |
|-------|-------------|
| **Parameters** | The only sheet the user edits. Yellow cells contain prices, targets, CAC, campaign discount, and USD/BRL exchange rate. Any change recalculates the entire database and dashboard. |
| **Database** | Transaction records (demo/artificial data). Revenue, Cost, and Profit columns use formulas that pull prices from the Parameters sheet. |
| **Calculations** | Aggregations via `SUMIFS` by Plan, Region, Billing Cycle, Add-on, New/Renewal, and Monthly Trend. Fully automatic. |
| **Dashboard** | KPI cards + 6 executive charts that react automatically to Parameters. |
| **Instructions** | Dashboard usage guide. |

## Key Indicators (KPIs)

- **Total Revenue (R$)**
- **Subscribers (units)**
- **Total Profit (R$)**
- **ARPU (R$)**
- **Average Ticket (R$)**
- **Profit Margin**
- **% of Target Achieved** (Revenue, Subscribers, and USD Exchange Rate)

## Visualizations

Six executive charts powered by Calculations sheet aggregations:

1. Revenue by Plan
2. Revenue by Region
3. Revenue by Billing Cycle
4. Revenue by Add-on
5. New vs Renewal
6. Monthly Revenue Trend

## How to Reproduce / Use

1. Open `Dashboard_Xbox_Professional.xlsx` in Microsoft Excel.
2. Go to the **Parameters** sheet and edit the **yellow** cells (prices, targets, discounts, CAC, exchange rate, etc.).
3. The dashboard and charts are recalculated automatically.
4. Use Excel filters/slicers to explore analytical views.
5. To simulate scenarios (e.g., increase Ultimate price or revenue target), just change the yellow values and observe the impact on KPIs and charts.

> Note: formulas depend on Excel's automatic calculation features; opening in Excel is recommended (not in editors without native formula support).

## Requirements

- Microsoft Excel (version with chart and `SUMIFS` support).
- No additional installation or external dependencies.

## Data Source

Transaction database contained in the **Database** sheet itself (artificial/demo data for challenge purposes), with fields such as Date, Cycle, Region, Channel, subscribed plan, and add-ons (EA Play, Minecraft Pass, Call of Duty Pass).
