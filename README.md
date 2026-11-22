# Colombo Road Accident Analysis (2020–2024)

## Project Overview

This project analyzes road accident statistics across police areas in Colombo, Sri Lanka, from 2020 to 2024.

The main objective is to identify accident trends, compare police areas, and present meaningful insights through data analysis and interactive visualizations.

The project uses Python for data cleaning and exploratory data analysis (EDA), and Microsoft Power BI for dashboard development.

## Objectives

- Analyze yearly road accident trends from 2020 to 2024.
- Identify police areas with the highest and lowest recorded accident counts.
- Compare accident statistics across different police areas.
- Create meaningful data visualizations.
- Develop an interactive Power BI dashboard.

## Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Google Colab | Python development environment |
| Microsoft Power BI | Interactive dashboard development |
| GitHub | Project version control and documentation |

## Dataset Information

**Source:** Department of Census and Statistics, Sri Lanka.

**Reference:** Statistical Abstract 2025 – Chapter VII, Table 7.5.

**Dataset link:** https://www.statistics.gov.lk/abstract2025/CHAP7/7.4%207.5%207.6.pdf

- Time period: 2020–2024
- Geographic coverage: Colombo police areas
- Number of police areas: 23
- Number of observations: 115, including one missing value

The dataset contains annual accident counts for each police area. The missing value is retained rather than treated as zero.

## Project Workflow

### 1. Data Collection
Collected official road accident statistics from the Department of Census and Statistics, Sri Lanka.

### 2. Data Cleaning
- Checked missing values.
- Checked duplicate records.
- Verified data types.
- Retained the original missing observation.
- Prepared the dataset for analysis.

### 3. Exploratory Data Analysis (EDA)

Performed the following analyses:

- Yearly accident analysis.
- Police area accident comparison.
- Identification of highest and lowest accident areas.
- Comparison of accident patterns across years.

### 4. Data Visualization

Created the following visualizations using Python:

- Yearly accident trend line chart.
- Top 10 police areas bar chart.
- Police area and year comparison heatmap.

### 5. Power BI Dashboard

Developed an interactive dashboard to present accident statistics using:

- Total accident KPI card.
- Yearly accident trends.
- Police area comparisons.
- Interactive filters for data exploration.

## Key Findings

Based on the current analysis:

- 2020 recorded the highest yearly total, with 1,915 accidents.
- 2024 recorded 1,623 accidents.
- Cinnamon Gardens recorded the highest cumulative count, with 1,446 accidents.
- Borella recorded the second-highest cumulative count, with 1,388 accidents.
- Bluemendhal recorded the lowest cumulative count, with 21 accidents.

These findings are based on the currently prepared police-area dataset and should be validated against the original source table before final publication.


## Limitations

- The analysis uses aggregated annual statistics rather than individual accident records.
- The dataset does not provide accident time, weather conditions, or individual accident severity.
- One observation is missing in the original table.
- The analysis describes recorded accident counts and does not establish the causes of accidents.

## Future Improvements

- Extend the analysis to other districts in Sri Lanka.
- Include accident severity and casualty statistics from additional official datasets.
- Develop more detailed geographical visualizations.
- Incorporate additional years when official data becomes available.

## Author

**Thisara Chethani**

BSc (Hons) Computing and Information Systems  
Faculty of Computing  
Sabaragamuwa University of Sri Lanka

---

*This project was developed as part of my Data Analytics learning.*
