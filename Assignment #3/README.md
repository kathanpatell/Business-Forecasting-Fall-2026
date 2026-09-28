# Forecasting Data Homework

## Project Overview

For this homework, I selected the U.S. monthly unemployment rate as the time-series dataset that I will use to practice forecasting models. The dataset contains 309 monthly observations from January 2000 through September 2025. The rate is reported as a percentage and is seasonally adjusted.

The data file was found in the Files section on Canvas, where it was uploaded by the professor. The underlying statistics are collected by the U.S. Bureau of Labor Statistics through the Current Population Survey. Information about the official series is also available from the Federal Reserve Bank of St. Louis FRED database.

## What Was Done

1. I downloaded the monthly unemployment-rate CSV file provided by the professor through Canvas.
2. I checked that the observations were arranged in monthly order and did not contain missing values.
3. I created a data dictionary explaining the date and unemployment-rate variables.
4. I described how the Current Population Survey collects the data, who conducts it, and how often it is collected.
5. I explained why the unemployment rate is an interesting dataset for forecasting.
6. I included basic R code showing how the CSV file can be imported in a future class.

No forecasting model was created for this homework because the next class will cover importing the data and creating a time-series variable in R.

## Files in This Repository

| File | Description |
|:-----|:------------|
| `US_Monthly_Unemployment_Rate_2000_2025.csv` | The monthly unemployment-rate data used for the project. |
| `Kathan_Patel_Forecasting_Data_HW.Rmd` | The R Markdown source file containing the four homework sections. |
| `Kathan_Patel_Forecasting_Data_HW.html` | The finished report produced by knitting the RMD file in RStudio. |
| `README.md` | A summary of the project and its files. |

## Data Variables

- `observation_date`: The month connected to each observation, written in `YYYY-MM-DD` format.
- `UNRATE`: The seasonally adjusted U.S. unemployment rate, measured as a percentage of the civilian labor force.

## Sources

- Course source: Data file uploaded by the professor in the Canvas Files section.
- [FRED: U.S. Unemployment Rate](https://fred.stlouisfed.org/series/UNRATE)
- [BLS: Current Population Survey](https://www.bls.gov/cps/cps_over.htm)
- [OSF: How to Make a Data Dictionary](https://help.osf.io/article/217-how-to-make-a-data-dictionary)
