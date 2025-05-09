# bikeshare-station-map
Mapped Austin's top bikeshare stations using SQL + R (ggplot2 + leaflet)

# 🚲 Bikeshare Station Map (Austin, TX)

This project analyzes Austin's top bikeshare stations using public data from Google BigQuery and visualizes the results with both static and interactive maps.

## 📊 What’s Inside

- **SQL analysis** in BigQuery to identify the top 10 bikeshare stations by total trips
- **Data export** as CSV for local analysis
- **R Markdown report** featuring:
  - A horizontal bar chart using `ggplot2`
  - A static map showing station locations and usage
  - An interactive leaflet map with zoom and station-level popups

## 📁 Files

| File | Description |
|------|-------------|
| `bikeshare-station-map.Rmd` | R Markdown report source |
| `bikeshare-station-map.html` | Rendered HTML report |
| `top_bikeshare_stations.csv` | Exported data from BigQuery |
| `bikeshare-station-map_files/` | Auto-generated folder containing plots |

## 🧰 Tools Used

- Google BigQuery (SQL)
- R + tidyverse
- ggplot2 for static data visualization
- leaflet for interactive geospatial mapping
- Git for version control

## 📌 Highlights

- Demonstrates data wrangling, joining, and filtering in SQL
- Showcases both static and interactive data visualization skills in R
- Follows a clean, professional Git workflow using RStudio and GitHub

---

## 🔗 Dataset Source

- [BigQuery Public Datasets – Austin Bikeshare](https://console.cloud.google.com/marketplace/product/bigquery-public-data/austin_bikeshare)

-
