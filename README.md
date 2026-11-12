# Mobile Sales Analysis Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Project-Portfolio%20Project-2ea44f)
![Focus](https://img.shields.io/badge/Focus-Data%20Analytics-0969da)

## Project overview

This portfolio project explores mobile-phone sales data through an interactive Power BI dashboard. It is designed to help a retail business review sales performance and compare products, locations, payment preferences and customer ratings.

## Dashboard preview

> Add your own dashboard screenshot here. In Power BI Desktop, open the report, take a clear screenshot, save it as `screenshots/mobile-sales-dashboard.png`, then replace this note with:
> `![Mobile Sales Dashboard](screenshots/mobile-sales-dashboard.png)`

## Business questions

- What are the headline sales, quantity, transaction and average-value KPIs?
- How does sales performance vary by city?
- Which brands and mobile models perform strongly?
- Which payment methods are used most often?
- How do quantity and sales trends vary over time and by weekday?
- What patterns appear in customer ratings?

## Dashboard features

- KPI cards for Total Sales, Total Quantity, Transactions and Average
- City-level sales map
- Monthly/daily quantity trend
- Mobile-model comparison
- Payment-method breakdown
- Customer-rating visual
- Weekday trend and brand performance table
- Slicers for month, model, payment method, brand and day name

## Tools and skills

- **Power BI Desktop** — dashboard design, visuals, slicers and interactive filtering
- **Data analysis** — KPI review, trend analysis and category comparisons
- **DAX / data modelling** — measures and model exploration (see `docs/dax-measures.md` for example templates)
- **SQL** — practice queries in `sql/analysis_queries.sql` (adapt table and column names to the actual source schema)

## Repository structure

```text
Mobile-Sales-Analysis/
├── powerbi/
│   └── Mobile-Sales-Dashboard.pbix
├── sql/
│   └── analysis_queries.sql
├── docs/
│   ├── data-dictionary.md
│   ├── dax-measures.md
│   ├── insights-template.md
│   └── interview-questions.md
├── screenshots/              # Add dashboard screenshots here
├── .gitignore
├── LICENSE-NOTE.txt
└── README.md
```

## How to open the project

1. Download or clone this repository.
2. Install [Power BI Desktop](https://www.microsoft.com/power-platform/products/power-bi/desktop).
3. Open `powerbi/Mobile-Sales-Dashboard.pbix`.
4. If Power BI asks for a data source or credentials, follow the prompt and update the source as needed.
5. Explore the report using the slicers and visuals.

## Analysis and findings

Add findings only after checking the actual dashboard. Use `docs/insights-template.md` to record the top-performing brand, model, city, payment method and time period, along with a business recommendation. Do not publish invented figures.

## Limitations and notes

- The PBIX file contains the report and its embedded data model. The original source dataset was not supplied separately in this repository.
- SQL and DAX files are learning/reference templates; verify field names and metric definitions against the actual model before reuse.
- Add screenshots and verified numerical insights before presenting this as a completed portfolio case study.

## Interview summary

“I created an interactive Power BI dashboard to explore mobile retail sales. It presents headline KPIs and allows users to compare sales across cities, brands, mobile models, payment methods, customer ratings and time periods. I used slicers to make the report interactive and to support business-focused exploration. My next step would be to validate metric definitions, document the source data and add a refresh process.”

## Author

Rehan Beldar  
Aspiring Data Analyst | Power BI | SQL | Excel  

Add your LinkedIn and GitHub profile links here before publishing.
