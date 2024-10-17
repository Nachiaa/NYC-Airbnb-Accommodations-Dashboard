# NYC Vaccination Analysis Shiny App

## Overview
This Shiny app provides interactive visualizations for COVID-19 vaccination data by country and manufacturer. Users can explore vaccination trends and filter data based on specific vaccines and countries.

## Files
- `ui.R`: Contains the user interface layout for the Shiny app.
- `server.R`: Contains the server logic, including data processing and plotting.
- `data/country_vaccinations.csv`: Contains country-level vaccination data.
- `data/country_vaccinations_by_manufacturer.csv`: Contains vaccination data by vaccine manufacturer.

## Installation
1. Install R and RStudio if you haven’t already.
2. Install required packages:
   ```r
   install.packages(c("shiny", "ggplot2", "dplyr", "plotly", "tidyr", "spreadr"))
