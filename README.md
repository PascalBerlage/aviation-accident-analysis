# Aviation Accident Fatalities: Statistical Analysis

## Overview
Statistical analysis of 5,568 historical aviation accident records to identify fatality trends by cause and aircraft type.

## Methods
- **Data:** Kaggle dataset (1948–present), cleaned and categorized
- **Analysis:** One-Way ANOVA with Tukey HSD, Linear Regression
- **Tools:** R (tidyverse)

## Key Findings
1. **Human-error accidents** have highest average fatalities (7.1 vs 5.5 for mechanical)
2. **Cargo aircraft** are most deadly (9.2 avg. fatalities vs 6.2 commercial)
3. **Fatality gap** between human and mechanical causes widened by 0.07 deaths/year (p < 0.001)

## Technical Details
- Cleaned raw data using `dplyr`
- Applied ANOVA to compare means across accident causes
- Used linear regression to model trends over time
- Visualized results with ggplot2

## Files
- `aviation_analysis.R` – Complete R Markdown analysis
- `aviation_accident_report.pdf` – Formatted project report
- `README.md` – This file
