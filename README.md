BrewMetrics — Coffee Sales Dashboard (2019–2022)
An interactive Excel dashboard analyzing coffee sales across four bean varieties, three international markets, and multiple roast and size segments — built to surface revenue trends and customer patterns through dynamic Pivot Table reporting.

Project Overview
DetailValuePeriodJan 2019 – Aug 2022Total Revenue$45,134Unique Customers913MarketsUnited States, Ireland, United KingdomCoffee TypesArabica, Excelsa, Liberica, RobustaToolMicrosoft Excel

Dashboard

📸 Add your dashboard screenshot here: ![Dashboard](images/coffee-dashboard.png)

The dashboard supports filtering by roast type, package size, loyalty card status, and date range — all charts update simultaneously based on active slicer selections.

Key Findings
1. 2021 was the only meaningful growth year (+13.6%)
Sales in 2019 and 2020 were nearly flat ($12,187 vs $12,118). Growth only materialised in 2021, where revenue reached $13,766 — driven by gains across all four coffee types.
2. Excelsa leads in total revenue, but Arabica is growing fastest
Excelsa generated the highest 4-year total ($12,306). However, Arabica grew 38% from 2019 ($2,927) to 2021 ($4,046) — the strongest growth trajectory in the product range. Robusta ranked last in every year at $9,005 total.
3. The US market accounts for 79% of all revenue
United States: $35,639 | Ireland: $6,697 | United Kingdom: $2,799. The UK declined sharply from $1,074 in 2020 to $643 in 2021 and just $130 in the first 8 months of 2022.
4. Loyalty card holders spend less per transaction than non-members
Non-loyalty customers averaged $46.48 per transaction vs $43.67 for loyalty card holders. The loyalty program does not appear to be driving larger basket sizes.
5. The 2.5 kg package drives 52.7% of total revenue
Despite being the highest-priced option, the largest pack size ($23,786) outsells all others combined — indicating a bulk-buying customer base.

Data Structure
Three source tables — orders (1,000 rows), customers (913 records), products (48 variants) — connected via Customer ID and Product ID. Dashboard built using Pivot Tables and Slicers on top of the consolidated orders table.

Tools Used
Microsoft Excel — Pivot Tables, Pivot Charts, Slicers, Timeline filter
Dataset: Coffee Sales (publicly available practice dataset)
