# U.S. LNG Forecasting Project

This project compares monthly U.S. LNG export volumes to South Korea, India, and China. I used the forecasting methods covered in class, forecast 12 months into 2026, and compared their historical fitted MSE.

Files in this folder:

- `Kathan_Patel_LNG_Forecasting_Project.Rmd` - R Markdown code and explanation
- `Kathan_Patel_LNG_Forecasting_Project.html` - completed HTML report to upload separately on Canvas
- `US_LNG_Export_Volumes_2017_2025.xlsx` - monthly EIA data used by the RMD

To knit the report, keep all three files in the same folder, open the RMD in RStudio, and click **Knit**. The R packages used are `readxl`, `fpp2`, and `TTR`.

The models compared are simple average, naive, naive with drift, seasonal naive, simple exponential smoothing, Holt, and Holt-Winters. Simple exponential smoothing had the lowest historical MSE for all three countries in this comparison.

Data source: U.S. Energy Information Administration.
