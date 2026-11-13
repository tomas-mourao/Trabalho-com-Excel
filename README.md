# Exploratory Data Analysis in R – European Values Study

Exploratory analysis of the **European Values Study** comparing attitudes and values between **Portugal and Finland**, written in R Markdown.

> **Course:** Exploratory Data Analysis · BSc in Data Science, ISCTE · Year 1, Semester 1

## Research questions
1. Does trust in neighbours differ between countries?
2. Does year of birth (generation) influence education level?
3. Does gender influence trust in people known personally?

## Methodology
- **Data preparation:** recoding missing values, median imputation and a new *Generation* variable (Baby Boomers, Gen X, Millennials, Gen Z).
- **Univariate analysis:** frequency tables and descriptive statistics.
- **Bivariate analysis:** cross-tabulations and charts relating country, generation, gender, education and trust.

## Tech stack
R · R Markdown · readxl · dplyr · ggplot2 · flextable · knitr

## How to run
Open `eda_report.Rmd` in RStudio, install the packages listed above if needed and click **Knit**. The data is read from `data.xlsx` in the same folder.

## Project structure
| File | Description |
|------|-------------|
| `eda_report.Rmd` | R Markdown source of the report |
| `eda_report.html` | Rendered report (open in a browser) |
| `eda_report.pdf` | Final report in PDF |
| `data.xlsx` | Dataset used in the analysis |

> The report is written in Portuguese.
