# Divvy Bike Usage & Neighborhood Income Analysis
### *Geospatial & Exploratory Data Analysis of Chicago Divvy Trips*

**Author:** William Ajayi  
**Tools:** Python (Pandas, GeoPandas, Matplotlib, Seaborn, Folium), Jupyter Notebook  
**Last Updated:** December 2025  

<img width="1024" height="683" alt="image" src="https://github.com/user-attachments/assets/8648a167-be98-4548-9d4b-6b1882803c7f" />

---

## Project Overview
This project analyzes Chicago’s Divvy bike trip dataset to understand how bicycle usage varies across neighborhoods and how these patterns relate to socioeconomic indicators such as median household income. Using geospatial analysis, exploratory visualizations, and income data integration, the project identifies regional disparities and provides insights relevant to equitable transportation planning.

---

## Tech Stack
- **Python** — data cleaning, feature engineering, geospatial processing  
- **Pandas / NumPy** — tabular analysis  
- **GeoPandas** — shapefile handling, spatial joins  
- **Matplotlib / Seaborn** — plots and statistical visualizations  
- **Folium** — interactive maps  
- **Jupyter Notebook** — workflow and narrative  

---

## Objectives
This project aims to:

- Analyze Divvy bike usage across Chicago neighborhoods  
- Map spatial ride density using geospatial tools  
- Merge neighborhood income data to explore socioeconomic trends  
- Identify disparities in access and usage  
- Produce insights that could support equitable transportation policy  

---

## Data Sources
- **Divvy Trip Data (CSV)** — cleaned dataset with start/end coordinates and timestamps  
- **Chicago Neighborhood Boundaries (Shapefile)**  
- **Income Data (CSV)** — median household income by neighborhood  
- **Engineered Features:** ride counts, total density, geographic region labels  

---

## Methods & Workflow

### **1. Data Cleaning & Preparation**
- Removed null values, standardized coordinate fields, and corrected datatypes  
- Engineered new variables such as ride counts, total density, and neighborhood labels  

### **2. Geospatial Mapping**
- Converted coordinate pairs into geometric points  
- Performed spatial joins with Chicago neighborhood boundaries  
- Built heatmaps and choropleth maps to visualize ride density  

### **3. Exploratory Data Analysis (EDA)**
- Summary statistics and distribution checks  
- Scatterplots, regression trends, and bar charts  
- Faceted visualizations comparing regional patterns  

### **4. Insight Generation**
- Identified disparities, emerging clusters, and socioeconomic patterns  
- Summarized insights into actionable recommendations  

---

## Visualizations Included
- **Ride Density Heatmap** — Divvy usage intensity by neighborhood  
- **Income vs. Divvy Usage Scatterplot** — socioeconomic correlation  
- **Regression Trendline Visualization** — direction + strength of relationship  
- **Regional FacetGrid Analysis** — North, West, South, Central comparisons  

---

## Key Insights
- **Divvy usage is highly concentrated in central and higher-income neighborhoods**, with significantly lower activity in many South and West Side regions.  
- **A positive relationship exists between median household income and total ride count**, suggesting that access and bike availability may disproportionately benefit higher-income communities.  
- **Geospatial heatmaps reveal clear regional clustering**, with downtown and North Side neighborhoods showing the highest ride density.  
- **Regional facet plots show distinct usage patterns by zone**, reinforcing that location-based factors heavily influence ridership behavior.

---

## Recommendations
- **Expand bike availability and station infrastructure** in underserved neighborhoods to improve accessibility.  
- **Partner with city planners** to target transportation equity gaps in South and West Side communities.  
- **Pilot incentives or pricing adjustments** to encourage ridership in low-usage areas.  
- **Analyze time-based features (hour, day, season)** to optimize station placement and resource allocation.

---
