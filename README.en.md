# dashboard-xbox

**English** · [Português (Brasil)](README.md)

[![Excel](https://img.shields.io/badge/Excel-xlsx-217346?style=flat-square&logo=microsoftexcel)](#) [![MIT License](https://img.shields.io/badge/License-MIT-f4c430?style=flat-square)](#)

## What it is

An **Xbox Game Pass sales dashboard built in Excel** (a data organization and visualization challenge): it turns raw sales data into KPIs, calculation tables (SUMIFS/participation) and a visual panel. It is an `.xlsx` file with 5 sheets: Parameters, Database, Calculations, Dashboard and Instructions.

## Status

A finished Excel file (challenge). Meant to be opened in Excel/LibreOffice/Google Sheets.

## Features

- **Parameters sheet**: plans and prices (Core/Standard/Ultimate, monthly/quarterly/yearly), add-ons (EA Play, Minecraft Pass, Call of Duty Pass), configurable goals and assumptions.
- **Database sheet**: 1,200 sales with ID, date, plan, cycle, region, channel, add-ons, type (new/renewal), quantity, revenue, cost and profit.
- **Calculations sheet**: revenue by plan, by region, participation and aggregates (SUMIFS).
- **Dashboard sheet**: KPIs (Total Revenue, Subscribers, Total Profit, ARPU, Average Ticket, Profit Margin), goal attainment and an analytical chart view.
- **Instructions sheet**: how to use it and what can be safely changed.

### KPIs (from the base, verified by the agent in the file)

| KPI | Value |
|-----|-------|
| Total revenue | R$ 1,155,626.77 |
| Subscribers | 21,915 |
| Total profit | R$ 892,646.77 |
| ARPU | R$ 52.73 |
| Average ticket | R$ 963.02 |
| Profit margin | 77.2% |

## Repository layout

```
dashboard-xbox/
├── Dashboard_Xbox_Professional.xlsx   # the dashboard (5 sheets)
├── contexto.txt                        # challenge briefing
└── README · LICENSE
```

## How to use

1. Open `Dashboard_Xbox_Professional.xlsx` in Excel/LibreOffice/Google Sheets.
2. Use the 'Instructions' sheet for guidance.
3. Edit only the yellow cells in the 'Parameters' sheet (the rest are automatic).

## Tests and quality

There are no automated tests — it is an Excel file. Validation was done by opening the file and checking the sheets, calculations and KPIs (see the table above).

## Development process

An individual project by Kelvin Oliveira, built with orchestrated AI agents and reviewed by the author. The sheet modeling, the calculations and the review are the author's.

## License and author

MIT — Copyright (c) 2026 Kelvin Rebelo de Oliveira.

**Author**: [Kelvin Oliveira](https://github.com/KelvinOliveiraCode) · [Portfolio](https://kelvinoliveiracode.github.io/portfolio/)
