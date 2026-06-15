# Marketing Campaign Performance Dashboard (Looker Studio)

![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat&logo=looker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=sql&logoColor=white)

🔗 [View Interactive Dashboard](https://datastudio.google.com/reporting/f56428e2-d3c8-405d-b76f-c6ce4d66b534)

## Description

Built an interactive marketing performance dashboard in Looker Studio, connected to a PostgreSQL database via a custom SQL query. The dashboard tracks ad spend efficiency and return on marketing investment (ROMI) across 11 campaigns, with calculated fields and interactive filters for deeper analysis.

![Dashboard Overview](dashboard_overview.png)

## My Tasks

- Connected Looker Studio to a PostgreSQL data source using a custom SQL query
- Built calculated fields for Ad Spend, CPC, CPM, CTR, and ROMI
- Designed a combo chart showing monthly Ad Spend (bars) and ROMI (line) over time, sorted chronologically
- Built a line chart tracking the number of active campaigns per month
- Created a campaign performance table with conditional heatmap formatting across Ad Spend, CPC, CPM, CTR, and ROMI
- Added interactive filters for campaign name and ad date range

## Result

The dashboard surfaces a clear efficiency picture across campaigns: spend and ROMI don't move together — a sharp ROMI spike (~190%) in early 2022 occurred during a period of relatively low spend, while the highest-spend period (April 2022) saw ROMI drop back to baseline. The campaign table highlights "Trendy" as the standout performer on ROMI (190.68%) despite minimal spend ($1.99k), while larger campaigns like "Expansion" and "Lookalike" operate at far lower efficiency relative to their budgets.
