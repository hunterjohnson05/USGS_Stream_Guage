# USGS_Stream_Guage
Summary: Function that creates .xlsx file of daily streamflow data between any dates for any USGS Stream Gauge.

How to use: Copy and paste the "R_code" script and run in Rstudio. After running, execute the function "USGS_Stream_Gauge_Retrieval". 

Inputs: USGS Gauge Station code, start date, end date, and file path of where the .xslx will be saved. 
Example: USGS_Stream_Gauge_Retrieval("1989-01-25", "2021-08-07", "11152500", "T:\\Hunter_Johnson\\Data\\Spreckles_daily.xlsx")

Outputs: .xslx of the daily data stored in the specified location, and a hydrograph of all the data in the R console.
