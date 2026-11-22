# Manufacturing Performance Dashboard

An interactive Power BI dashboard that tracks manufacturing performance across product types, countries, warehouse locations, and time. It helps answer where production cost is concentrated, which products and countries drive volume, and how efficiently each country produces.

<img src="image/Manufacturing_Dashboard%20(1).png" alt="Manufacturing Performance Dashboard" width="100%">

## Key Metrics (KPI Cards)

| Metric | Description |
|---|---|
| **Avg. Production Cost** | Average production cost per product record |
| **Total Quantity Produced** | Total units produced |
| **Avg. Production Cost per Unit** | Average cost efficiency (production cost relative to quantity produced) |

## Visualizations

- **Production Cost by Product Type**: total production cost for each product category
- **Production Volume by Country**: share of total quantity produced by each country (donut chart)
- **Product Distribution Across Warehouse Location**: quantity produced per warehouse region (West, East, North, South)
- **Monthly Production Trend**: quantity produced by month
- **Total Production by Product Type**: quantity produced per product category
- **Cost Efficiency by Country**: average cost per unit by country

## Filters

Slicers let you filter the whole dashboard by **Year**, **Product Type**, and **Country**.

## Key Insights

- **Automobiles and Textiles** have the highest production cost (about $2.2M each), while **Machinery** is the lowest (about $1.7M).
- **Textiles and Automobiles** also lead in volume (about 115K units each); Machinery produces the least (88K).
- **Production volume is evenly spread across countries**, each contributing roughly 19% to 21% of the total.
- **West** is the largest warehouse location (140K units) and **South** the smallest (124K).
- **Production peaks in May (52K units)** and drops sharply from October to December (33K to 35K).
- **USA has the highest cost per unit ($29.71)** and **Japan the lowest ($22.41)**.

## Tools

- Microsoft Power BI Desktop
- DAX and Power Query for data cleaning and calculated columns

## Project Structure

```
manufacturing-performance-dashboard/
├── Power-BI/
│   └── Manufacturing_performance.pbix   # Power BI report file
├── image/
│   └── Manufacturing_Dashboard (1).png  # Dashboard screenshot
└── README.md
```

## How to Use

1. Download or clone this repository.
2. Open `Power-BI/Manufacturing_performance.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Use the Year, Product Type, and Country slicers to explore the data.
