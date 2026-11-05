# Blinkit Sales Dashboard

An interactive Blinkit sales analysis dashboard built with Microsoft Power BI. The report presents sales KPIs, outlet performance, product-category analysis, and interactive filters.

## Dashboard Preview

![Blinkit Sales Dashboard](screenshots/blinkit-dashboard.png)

## Project Objectives

- Analyze overall sales performance.
- Examine product category and fat-content performance.
- Compare outlet performance.
- Understand sales distribution across outlet characteristics.

## Tools and Technologies

- Microsoft Power BI Desktop

Microsoft Power BI is the only report-development tool verified from the project files. Specific DAX measures, Power Query transformations, and the Power BI version are not documented in the repository.

## Key Performance Indicators

| KPI | Displayed value | What it represents |
| --- | ---: | --- |
| Total Sales | $1.20M | The total sales value displayed by the report. |
| Average Sales | $141 | The average sales value displayed by the report. |
| Number of Items | 8,523 | The number of items displayed by the report. |
| Average Rating | 3.9 | The average rating displayed by the report. |

These descriptions reflect the report labels and displayed values; the underlying calculation definitions are not documented separately.

## Dashboard Features

The dashboard provides analysis views for:

- Outlet Establishment
- Fat Content
- Item Type
- Outlet Size
- Outlet Location
- Outlet Type

## Interactive Filters

- Outlet Location Type
- Outlet Size
- Item Type

## Key Observations

The following are direct observations from the supplied dashboard screenshot, not business conclusions:

- The headline cards display total sales of $1.20M, average sales of $141, 8,523 items, and an average rating of 3.9.
- The Outlet Establishment visual shows sales values by year and a visible high point of $205K in 2018.
- The Outlet Type table compares total sales, number of items, average sales, average rating, and item visibility across outlet types.

Further data-level analysis would be required to validate trends, explain causes, or draw business conclusions beyond these visible observations.

## Dataset Information

The dataset source and provenance are not documented in the repository. No external dataset link or download location is asserted here.

## How to Run

1. Clone or download this repository.
2. Open `Blinkit_Sales_Dashboard.pbix` in Microsoft Power BI Desktop.
3. Interact with the report visuals and filters.

## Limitations

- The PBIX file is required to inspect and interact with the report.
- The repository does not include a documented dataset source or separate data extract.
- The screenshot is a static preview and does not provide report interactivity.
- Calculations and transformations inside the PBIX are not described because they were not independently documented in the repository.

## Project Structure

```text
.
├── README.md
├── .gitignore
├── Blinkit_Sales_Dashboard.pbix
└── screenshots/
    ├── .gitkeep
    └── blinkit-dashboard.png
```

## Author

[pawan-aicode](https://github.com/pawan-aicode)
