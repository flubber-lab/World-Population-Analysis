# Population Data Analysis

This repository contains Python scripts for analyzing population data from the World Bank dataset. The dataset includes demographic indicators such as total population, gender distribution, age dependency ratios, and migration trends for various countries, with a focus on **Aruba** and the **Africa Eastern and Southern** region.

## Project Overview
The goal of this project is to analyze population trends and demographic indicators using Python. The analyses include:
- Population growth over time.
- Gender distribution.
- Age dependency ratios.
- Aging population trends.
- Migration patterns.
- Working-age population analysis.
- Regional comparisons.

The results are visualized using `matplotlib` and `seaborn` for better understanding and interpretation.

---

## Dataset Description
The dataset used in this project is sourced from the World Bank and contains the following key indicators:
- **Total Population**: `SP.POP.TOTL`
- **Male Population (% of total)**: `SP.POP.TOTL.MA.ZS`
- **Female Population (% of total)**: `SP.POP.TOTL.FE.ZS`
- **Age Dependency Ratios**: `SP.POP.DPND.YG` (young), `SP.POP.DPND.OL` (old)
- **Population Aged 65+ (% of total)**: `SP.POP.65UP.TO.ZS`
- **Net Migration**: `SM.POP.NETM`
- **Working-Age Population (15-64)**: `SP.POP.1564.TO.ZS`

The dataset is in a wide format, with years as columns. The scripts reshape the data into a long format for easier analysis.

---

## Analyses Performed
The following analyses were performed:
1. **Population Growth Analysis**: Visualized the total population growth over time for Aruba and Africa Eastern and Southern.
2. **Gender Distribution Analysis**: Compared male and female population percentages over time.
3. **Age Dependency Ratios**: Analyzed young and old dependency ratios.
4. **Aging Population Analysis**: Examined the percentage of the population aged 65 and above.
5. **Migration Analysis**: Studied net migration trends.
6. **Working-Age Population Analysis**: Analyzed the percentage of the population aged 15-64.
7. **Population Pyramid**: Created a population pyramid to visualize age and gender distribution.
8. **Regional Comparison**: Compared population growth between Aruba and Africa Eastern and Southern.
9. **Historical Trends and Projections**: Used linear regression to predict future population growth.

