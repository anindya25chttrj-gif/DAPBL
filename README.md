# 🌾 Global Agricultural Crop Yield & Environmental Impact Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Folium](https://img.shields.io/badge/Folium-Geospatial-green)

A data-driven exploratory analysis investigating how environmental factors and agricultural inputs influence global crop productivity.

---

## 📊 Project At a Glance
* **Dataset Size**: 28,242 global records[cite: 5]
* **Geographic Scope**: 101 Countries (`Area`)[cite: 5]
* **Target Metric**: Crop Yield (`hg/ha_yield` - hectograms per hectare)[cite: 5]
* **Key Drivers**: Annual Rainfall, Pesticide Usage, Average Temperature[cite: 5]

---

## 🛠️ Key Workflow & Steps
1. **Data Cleaning & Imputation**: Handled missing climate entries using regional median transformations.
2. **Exploratory Data Analysis (EDA)**: Visualized multi-variable relationships and correlations.
3. **Statistical Testing**: Tested linear dependencies using Pearson correlation.
4. **Geospatial Mapping**: Built an interactive global map displaying country-level yields.

---

## 📈 Visualizations & Outputs

| Feature | File / Description |
| :--- | :--- |
| **Scatter Plots** | `scatter_plots.png` — Yield vs. Rainfall, Pesticides & Temperature |
| **Correlation Heatmap** | `correlation_heatmap.png` — Matrix of feature interdependencies |
| **Interactive Map** | `folium_map.html` — Global choropleth / marker visualization |

---

## 💡 Key Insights
* **Climatic Sweet Spots**: Peak productivity concentrates in moderate rainfall bands (500mm–2,000mm/year) and temperatures between 10°C and 25°C.
* **Global Correlation**: Macro-level Pearson correlation between global rainfall and yield across *all* crops combined is near zero ($r = 0.0010, p = 0.8716$), proving that crop-specific segmentation is essential.
