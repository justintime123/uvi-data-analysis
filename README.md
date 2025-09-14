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

- The below charts depict % observations for UV index categories of high and very high every 5 years.
- Ratings of high and above require sunscreen and recommended cover during peak hours.

![Image](https://github.com/user-attachments/assets/06705359-81d2-428f-bf37-b5e7f7b823ef)
*All-sky distributions over the years. high is uv index 6-7, and very high is 8-10.*


![Image](https://github.com/user-attachments/assets/476afe7d-d9c9-45b3-9a14-b3f85b7585ac)
*Clear-sky distributions over the years. high is uv index 6-7, and very high is 8-10.*

## Discussion
See [Analysis](https://docs.google.com/document/d/1J_YixFedP1f0STpI05tjxHHzvOOlKxIdXTCIJais4fQ/edit?usp=sharing) for discussion and more visualizations.

## Technologies 
- Python:
  - Pandas
  - Matplotlib
