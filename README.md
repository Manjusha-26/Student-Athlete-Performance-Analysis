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
```r
install.packages(c("ggplot2", "readr", "dplyr", "tidyr", "reprex", "stringr"))```

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
![Uploading image.png…]()


## Visualizations
- Box plots and bar graphs illustrate the distribution and differences in APR rates over the years and between genders.

# Results

## General Trends
- APR rates have shown a gradual improvement over the observed years.

## Gender Disparities
- Female athletes tend to have higher APR rates than male athletes.

## Sport-Specific Trends
- Certain sports exhibit gender-exclusive participation which affects the APR rates observed.

# Conclusion
The analysis highlights the progress in academic performance among student-athletes, with notable differences across sports and between genders. Efforts to improve APR should consider these disparities to target improvements effectively.
