# SQL Project: Understanding Life in Chicago 

## Project Overview
This project explores various aspects of life in Chicago using SQL and publicly available datasets. It brings together crime records, public school data, and socioeconomic indicators to provide insights into safety, education, income inequality, and community challenges across the city.

As part of this exploratory data analysis, we use **SQLite** to query and combine datasets and uncover patterns in community well-being, school safety, crime distribution, and poverty.

### Datasets Used
- **Socioeconomic Indicators (2008–2012)**
Contains six public health-related socioeconomic metrics and a hardship index for each of Chicago's community areas.
  ➤ Fields include: per capita income, poverty rate, unemployment rate, education level, and crowding.
- **Chicago Public Schools (2011–2012)**
School-level performance data including school type, safety score, and student support indicators.
- **Chicago Crime Data (2001–present)**
Detailed crime reports (minus the most recent 7 days) including case number, primary type, location, and community area.

### Tools Used
- SQLite (via JupyterLab SQL magic commands)
- JupyterLab Notebook (for queries, outputs, and visuals)

### Key SQL Tasks Performed
- Counted total number of crimes recorded
- Identified communities with per capita income < $11,000
- Queried crimes involving minors or child victims of kidnapping
- Listed unique crime types reported on school grounds
- Analyzed average school safety score by school type
- Identified top 5 communities with the highest poverty rates
- Found the most crime-prone community area
- Used subqueries to extract:
  - Community with highest hardship index
  - Community with the most crime reports

### Findings & Insights
- Riverdale and Fuller Park have the lowest per capita incomes: $8,201 and $10,432, respectively.
- Austin is the most crime-prone area based on reported incident count.
- Schools experienced crimes such as battery, criminal damage, narcotics violations, and assault.
- High schools generally have better safety scores than elementary and middle schools.
- The community with the highest hardship index is Riverdale.
- Poverty is heavily concentrated in five specific community areas — all with over 40% of households below the poverty line.

### Takeaways
This analysis provides a data-driven snapshot of inequality and public safety across Chicago. By combining multiple datasets with structured queries, we uncovered relationships between **income, crime, and education**, helping stakeholders and policymakers focus their efforts on the most vulnerable communities.
