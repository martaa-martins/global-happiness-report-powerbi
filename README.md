# 🌍 Global Happiness Trends Dashboard (2015–2023)
**Overview**

This project features an interactive Power BI dashboard analyzing global happiness trends from 2015 to 2023 using data from the World Happiness Report. 

The main question guiding this dashboard is:

*How has national happiness evolved over time, and which factors most strongly drive changes across countries?*

**Data Preparation & Modeling**

- Data ingestion and transformation were performed using Power Query
- Annual CSV files were standardized and appended into a unified table
- Country-year records form the base grain of analysis
- Measures and KPIs were created using DAX
- The data model supports year filtering, country-level drill-downs, and cross-visual interactions

**Key KPIs**

- Average Happiness Score
- Average Ranking
- Average GDP per Capita
- Average Social Support

**Custom Metric — Weighted Happiness Index**

A composite index combining multiple well-being dimensions to provide a more nuanced view of happiness drivers:

*(0.231 × GDP per Capita) + (0.208 × Social Support) + (0.218 × Healthy Life Expectancy) + (0.183 × Freedom to Make Life Choices) + (0.026 × Generosity) + (0.135 × Perceptions of Corruption)*

This index enables clearer year-over-year comparisons and country-level decomposition of happiness drivers.

**Dashboard Highlights**

- Global overview of happiness trends by year
- Country-level trend analysis (2015–2023)
- Regional comparison via map visualizations
- Relationship between GDP per capita and happiness
- Interactive filters, tooltips, and bookmarks
- Multiple chart types (cards, bar charts, line charts, maps, scatter plots, donut charts) are used to support clear comparative analysis and storytelling.

**Skills Developed with this Project**

- Power BI
- DAX (custom KPIs and composite index)
- Power Query (data preparation)
- Data modeling
- Data visualization & storytelling

**How to Use?**

1. Download the .pbix file
2. Open it in Power BI Desktop
3. Refresh data if needed
4. Use year and country filters to explore insights

**Notes**

This project was developed for academic purposes and refined to meet professional portfolio standards.

The dataset is publicly available and included for reproducibility.
