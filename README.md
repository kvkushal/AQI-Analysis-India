# AQI Analysis of Indian Cities (Power BI)

> Visual analytics of air quality across 25+ Indian cities (2015–2017) using Microsoft Power BI. Interactive dashboards reveal pollutant trends, city-wise risk, and seasonal patterns.

![Air Quality Trends](docs/screenshots/AirQualityTrends.png)

![City-wise Comparison](docs/screenshots/City-wiseComparison.png)

![Pollutant Level Analysis](docs/screenshots/PollutantLevelAnalysis.png)

![AQI Insights](docs/screenshots/AQIInsights.png)

---

## 🚀 Overview
This project transforms raw environmental data into actionable insights with Power BI:
- **City-wise pollution burden** (Delhi, Ahmedabad, Gurugram, Patna, Talcher, etc.)
- **Temporal patterns** (winter spikes, monsoon dips)
- **Pollutant relationships** (PM2.5 vs PM10 correlation; NOx hotspots)
- **AQI bucket distribution** by region and season

---

## ▶️ Quick Tour
- **Power BI Dashboard (.pbix)**: [`AQI Analysis India.pbix`](AQI%20Analysis%20India.pbix)
- **Data file (CSV)**: [`city_day.csv`](city_day.csv)
- **Report (PDF)**: [`docs/AQI Analysis India.pdf`](docs/AQI%20Analysis%20India.pdf)

---

## 📊 Dashboards & Highlights

### Overall AQI Trends
![Dashboard 2](docs/screenshots/dashboard-2.png)
- National monthly AQI trends
- AQI bucket mix
- Top polluted cities over time

### Pollutant Analysis
![Dashboard 3](docs/screenshots/dashboard-3.png)
- PM2.5 vs PM10 scatter
- NO/NO2/NOx temporal hotspots
- Seasonal variation (Oct–Feb spikes)

### City Comparisons
![Dashboard 4](docs/screenshots/dashboard-4.png)
- Treemap of frequent poor-AQI cities
- Bubble map by average AQI
- Heatmap of city-specific monthly severities

> **Key observations:** PM2.5 & PM10 dominate AQI; NOx peaks Oct–Feb; Delhi, Gurugram, Patna, Talcher are hotspots; coastal cities fare better.

---


---

## 🧰 How to Use
### View the work (no setup)
1. Open the **PDF** in `/docs` for a concise report.
2. Browse screenshots in `/docs/screenshots/`.

### Open in Power BI Desktop
1. Install **Power BI Desktop** (Windows).
2. Open `AQI Analysis India.pbix`.
3. Explore pages, slicers, and filters interactively.

---

## 📝 Data
- **File:** `city_day.csv`
- **Source:** Public AQI dataset (2015–2017) with pollutants: PM2.5, PM10, NO, NO2, NOx, CO, O3.
- **Columns:** Date, City, pollutant levels, AQI, AQI bucket.
- **Cleaning:** handled missing values, standardized pollutant columns, created DAX measures for averages and AQI bucket percentages.

---

## 🔍 Methodology (Power BI)
- Visual types: line/area charts, bar/column charts, treemaps, maps, scatterplots, donuts, heatmaps, decomposition trees.
- Interactivity: slicers for **City**, **Year/Month**, **Pollutant**.
- DAX measures: average pollutants, AQI bucket distribution %, YoY trend.

---

## 🪪 License
MIT — feel free to reuse with attribution.

---
