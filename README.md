# Student-Athlete Performance Analysis

## Overview
This repository contains an analysis of Academic Progress Rates (APR) for NCAA Division I student-athletes, spanning from 2004 to 2014. The focus is on identifying trends and discrepancies in APR across different sports and between genders.

## Data
The dataset includes APR scores for student-athletes across various sports at NCAA Division I schools. Data was sourced from publicly available NCAA records.

## Dependencies
This analysis was performed using R. Required libraries include:
- `ggplot2`
- `readr`
- `dplyr`
- `tidyr`
- `reprex`
- `stringr`

To install these libraries, use:
```r install.packages(c("ggplot2", "readr", "dplyr", "tidyr", "reprex", "stringr"))```

# Files
- Student-athlete_performance_analysis.pdf - A knitted file of the R markdown file
- Student_athlete_performance_analysis.rmd - A pdf of the R file.

# Analysis Workflow

## Importing Libraries
- Libraries necessary for the analysis are loaded.

## Loading and Tidying Data
- Data is loaded from a TSV file and tidied for analysis.


## Cleaning the Data
- Data cleaning is performed to remove any outliers, particularly negative APR rates.

## Detailed Observations
- **APR rates increase gradually from 2004 to 2014.**
- **Notable increases in median APR rates are observed every four years.**

## Gender Analysis
- Breakdown of average APR rates by gender showing higher rates for female athletes consistently over the years.


## Visualizations
- Box plots and bar graphs illustrate the distribution and differences in APR rates over the years and between genders.

## Visualization - 1
<img width="716" alt="image" src="https://github.com/user-attachments/assets/a4be66d4-e10a-43c3-a963-8f1587e39c01">

## Visualization - 2
<img width="712" alt="image" src="https://github.com/user-attachments/assets/dafdca91-6da7-456b-9607-57f15f340780">


## Visualization - 3
<img width="715" alt="image" src="https://github.com/user-attachments/assets/ac4b5613-39cb-48e3-8ba9-eb5c9d2051e2">

## Visualization - 4
<img width="694" alt="image" src="https://github.com/user-attachments/assets/7d65efbf-e671-444a-aba9-1067e62823f6">


# Results

## General Trends
- APR rates have shown a gradual improvement over the observed years.

## Gender Disparities
- Female athletes tend to have higher APR rates than male athletes.

## Sport-Specific Trends
- Certain sports exhibit gender-exclusive participation which affects the APR rates observed.

# Conclusion
The analysis highlights the progress in academic performance among student-athletes, with notable differences across sports and between genders. Efforts to improve APR should consider these disparities to target improvements effectively.
