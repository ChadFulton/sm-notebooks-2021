# Example notebooks for Statsmodels in 2021

[Statsmodels](https://www.statsmodels.org/stable/index.html) contains many poweful statistical tools, but there aren't always enough examples of how and when to use it. In addition, as new features are added and some old components are deprecated, older examples can become obsolete. This set of example notebooks is intended to showcase some of the ways that Statsmodels can be used for data science and econometrics, with a plan to add new notebooks approximately every week in 2021. The focus will generally, but not exlusively, be on time series.

More generally, this project has two other aims:

1. Incorporate other pieces of the Python data science ecosystem
2. Identify areas and ways in which Statsmodels can be improved (for example, models that are missing, functions that don't work well, or improvements to better itegrate with the general ecosystem)

In addition to helping me explore new topics, hopefully these notebooks will provide some examples that will be useful to the Python community.

## Table of Contents

- `000-sm-notebooks-2021.ipynb`: "Example notebooks for Statsmodels in 2021". Contains an overview of this project.
- `001-etl-data-covid-19.ipynb`: "ETL Data - COVID-19 datasets". Describes three ETL strategies for the COVID-19 datasets that will be used for part of this project (CSV files, API calls, and Google BigQuery queries), and shows three visualizations using the data.
- `002-seasonal-adjustment.ipynb`: "Seasonal adjustment - COVID-19 cases". Shows how to use several methods from Statsmodels to seasonally adjust data, where the application is seasonally adjusting new cases of COVID-19 in the U.S.