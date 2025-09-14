# uvi-data-analysis
Time series analysis of UV Index data in NYC from 2000 to 2025

## Project Overview

## Data
- I requested UV index time series data from NOAA (found [here](https://www.cpc.ncep.noaa.gov/products/stratosphere/uv_index/uv_annual.shtml)) for New York City from 2000 to 2025.
- The dataset contains Valid Date, Clear-sky UVI, and All-sky UVI columns. 
  - Clear-sky UVI is the UVI assuming no cloud cover. It’s a theoretical value that’s useful for examining the maximum potential UV damage. 
  - All-sky UVI takes into account cloud cover and atmospheric conditions. So it’s more reflective of real UVI readings you’d see in a weather app or forecast.
  - Since clouds can dissipate UV rays, clear-sky UVI tends to be larger than all-sky UVI.
 
## Visualizations

![Image](https://github.com/user-attachments/assets/06705359-81d2-428f-bf37-b5e7f7b823ef)
 
## Discussion
See [Analysis](https://docs.google.com/document/d/1J_YixFedP1f0STpI05tjxHHzvOOlKxIdXTCIJais4fQ/edit?usp=sharing) for discussion.

## Technologies 
- Python:
  - Pandas
  - Matplotlib
