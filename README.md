📊 Tableau Data Visualization Project – Data Technician Bootcamp

📌 Overview

This repository contains the Tableau portion of the Week 2 workbook completed during the Data Technician Bootcamp by LeepTalent. The project focuses on building interactive dashboards and telling data-driven stories using a range of chart types — skills that are directly applicable to retail and sales analysis. Using datasets on employment, global health, and music streaming, the workbook demonstrates how to filter, calculate, and visualise data to uncover actionable insights.

The deliverable is a set of published Tableau Public dashboards that showcase end‑to‑end visual analytics: from data connection and worksheet design to dashboard assembly and sharing.

🛠️ Skills Demonstrated

Interactive Dashboards
Combined multiple worksheets into cohesive dashboards (e.g., “Global Health Dashboard”, “GB Employment Dashboard”).

Added global filters (e.g., Country, Year) that apply across sheets.

Used filter cards and quick filters for user‑driven exploration.

Published dashboards to Tableau Public for interactive sharing.

Filters & Slicers

Applied Top N filters (e.g., top 5 countries by average life expectancy).

Used quick filters (single‑value dropdown, multi‑select) on dimensions like Country and Continent.

Filtered to the most recent year using calculated fields or date filters.

Made filters global across a dashboard for coordinated views.

Calculated Fields

Created percentage of total calculations (e.g., population by gender as % of total).

Used date calculations to isolate the latest year.

Built aggregations (average life expectancy per continent).

Leveraged table calculations for dynamic insights.

Chart Types & Visualizations

Chart Type	Usage in Project

Bar Chart	Average life expectancy by continent; cancer cases by country; GB employment change by industry
Line Chart	Life expectancy trend over time for top 5 countries
Pie Chart	Population distribution by gender (latest year, selected country)
Map (Symbol Map)	GB employment change by city (interactive UK map)
Scatter Plot	Relationship between life expectancy and BMI, coloured by continent
Heatmap / Treemap	Cancer cases by country (part of the Global Health dashboard)
Data Storytelling
Derived actionable insights from each dataset:

GB Employment: Visualised regional employment shifts and industry changes using a map and bar charts.

Global Health: Identified disparities in life expectancy and BMI across continents; reflected that BMI alone is not a reliable predictor of life expectancy. Suggested NHS use for preventive care (e.g., cancer screening based on country of origin).

Spotify (optional): Explored genre popularity, artist trends, and audio features (energy, valence) to inform music‑industry decisions.

Designed dashboards with clear titles, labels, and colour schemes to guide the viewer’s eye.

Transfer to Retail & Sales: The same techniques — filtering by region/time, Top N analysis, calculated profit margins, and dashboard storytelling — are directly applicable to retail data (e.g., top‑selling products, sales by store, customer segmentation).

📂 Project Tasks & Deliverables

Day 1: Tableau Versions & GB Employment Dashboard
Compared Tableau Public, Reader, and Desktop, noting limitations of the free Public version (cloud‑only saves, limited data sources, no local file saving).

Built an interactive GB Employment dashboard (2011–2014) featuring:

A map of average % change by city.

Bar charts for change by industry and sub‑industry.

Filters for exploration.

Published to Tableau Public:
🔗 GB Employment Dashboard

<img width="1687" height="905" alt="image" src="https://github.com/user-attachments/assets/2e6c8827-5f4a-41b9-855b-a23200cfd7e9" />


Day 2: Global Health Insights (GapminderHealth)

Created five worksheets and combined them into a “Global Health Dashboard”:

Life Expectancy by Continent – bar chart, filtered to latest year, sorted.

Life Expectancy Trend – line chart for top 5 countries by average life expectancy.

Population by Gender – pie chart with % of total and country filter.

Life Expectancy vs BMI – scatter plot coloured by continent, with filter.

Cancer Cases by Country – additional visual (heatmap/treemap) chosen by the analyst.

Applied a global Country filter so users can explore one country across all charts.

Reflection: BMI is not an accurate predictor of life expectancy on its own; Africa lags in both metrics; NHS could use country‑of‑origin data for targeted preventive care.

Published to Tableau Public:
🔗 Global Health Dashboard

<img width="1917" height="947" alt="image" src="https://github.com/user-attachments/assets/16724007-386f-4bee-a8b6-5b2da5b70727" />


Day 2 (Optional): Spotify Features Analysis

Imported SpotifyFeatures.xlsx and explored trends.

<img width="1709" height="912" alt="image" src="https://github.com/user-attachments/assets/b9ec3b7b-6642-4108-bc3a-b448be70fa7b" />


Visualisations included:

Top 10 most popular genres (pie chart).

Most popular tracks by artist (bar chart).

High energy vs low energy genres (bar chart coloured by energy).

Findings: Ska and Comedy tracks tend to be short and energetic; most artists have few hit songs vastly more popular than the rest; genre preferences are relatively even among the top 10.
