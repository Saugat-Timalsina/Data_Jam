\# Wealth-Based Differences in Emergency Department Length of Stay Across New York City Hospitals



\## Research Question



How is neighborhood wealth, measured by the median household income of the area in which a hospital is located, associated with emergency department length of stay across New York City hospitals?



\## Study Design



This is an observational hospital-level association study.



Hospital-neighborhood median household income represents the socioeconomic context of the ZIP Code Tabulation Area (ZCTA) in which a hospital is located. It should not be interpreted as the income of patients treated at that hospital.



\## Data Sources



\- CMS Timely and Effective Care – Hospital

\- CMS Hospital General Information

\- U.S. Census Bureau 2024 American Community Survey 5-Year Estimates, Table B19013



\## Analytic Sample



\- 138,084 original CMS measure records

\- 4,658 OP-18a hospital records

\- 33 NYC hospitals identified across the five NYC counties

\- 31 hospitals with usable numeric OP-18a values

\- 31 of 31 hospitals successfully matched to ACS ZCTA median household income



\## Primary Result



Across 31 NYC hospitals, hospital-neighborhood median household income showed little association with median emergency department length of stay.



\- Pearson r = -0.094, p = 0.617

\- Spearman rho = -0.052, p = 0.782

\- Regression coefficient = -0.93 minutes per $10,000 higher neighborhood income

\- 95% CI = -4.69 to 2.83 minutes

\- R-squared = 0.0087



The findings did not support a meaningful association between hospital-location median household income and ED length of stay.



\## Repository Structure



\- `data/` — original CMS and ACS datasets

\- `notebooks/` — complete Jupyter analysis notebook

\- `output/` — cleaned dataset, analysis tables, HTML notebook, and poster-ready figures



\## Important Limitation



Hospital ZIP/ZCTA income is not patient income. NYC hospitals may serve patients from neighborhoods and boroughs far beyond the hospital's immediate location. The study therefore evaluates the socioeconomic context of hospital location rather than patient socioeconomic status.

