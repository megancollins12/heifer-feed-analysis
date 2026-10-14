
# Heifer Feed Analysis — Statistical Comparison of Feeding Methods

## Project Overview

This project examines the relationship between feeding methods, supplement levels, and total weight gain in heifers using R programming and statistical hypothesis testing.

The objective was to determine whether GROUP and PRECISION feeding methods produced significantly different average weight gains at two supplement levels: 0.5% and 1.0%.

## Research Question

Do GROUP and PRECISION feeding methods result in statistically significant differences in average heifer weight gain at different supplement levels?

## Tools and Technologies

- R Programming
- RStudio
- tidyverse
- ggplot2
- Descriptive Statistics
- Welch's Two-Sample t-Test
- Data Visualization

## Dataset

The analysis uses the `heifer_mod.csv` dataset.

Key variables include:

- **Treatment:** GROUP or PRECISION feeding method
- **Level:** Supplement level (0.5% or 1.0%)
- **tgain:** Total weight gain in pounds

## Methodology

The following analytical techniques were applied:

1. Data preparation and exploration
2. Descriptive statistical summaries
3. Boxplots comparing feeding methods
4. Histograms examining weight gain distributions
5. Normal Q-Q plots assessing normality
6. Welch's two-sample t-tests
7. Statistical interpretation of results

## Key Findings

### Supplement Level: 0.5%

- GROUP average weight gain: 185.1 lbs
- PRECISION average weight gain: 128.5 lbs
- p-value: 0.0013

**Finding:** A statistically significant difference was observed between the two feeding methods. GROUP feeding resulted in higher average weight gain.

### Supplement Level: 1.0%

- GROUP average weight gain: 197.9 lbs
- PRECISION average weight gain: 226.3 lbs
- p-value: 0.1117

**Finding:** Although PRECISION feeding produced a higher average weight gain, the difference was not statistically significant at the 0.05 significance level.

## Conclusion

The findings suggest that feeding methods may influence heifer weight gain differently depending on supplement levels.

At the 0.5% supplement level, GROUP feeding demonstrated significantly higher average weight gain.

At the 1.0% supplement level, there was insufficient statistical evidence to conclude that the feeding methods produced different mean weight gains.

## Project Files

- `MiniProject3_MRC.Rmd` — R Markdown analysis and code
- `MiniProject3_MRC.pdf` — Complete statistical analysis report

## Skills Demonstrated

- Statistical hypothesis testing
- Exploratory data analysis
- R programming
- Data visualization
- Statistical interpretation
- Communicating analytical findings

## Author

Megan Collins

M.S. Data Science & Analytics Candidate  
Clemson University
