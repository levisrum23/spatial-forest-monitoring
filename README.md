# spatial-forest-monitoring
"Geospatial visualization tool for tracking plantation health (NDVI) in Indonesia using Python and Folium."

# Geospatial Forest Health Monitor 🛰️🌲

### 📋 Overview
Managing large-scale agroforestry plantations in Indonesia requires efficient monitoring systems. Ground surveys are slow and expensive. 

This project demonstrates a **Remote Sensing** approach to monitoring. It simulates satellite-derived NDVI (Normalized Difference Vegetation Index) data to visualize plantation health interactively. It allows Mill Managers to identify "Hotspots" of deforestation or pest infestation instantly.

### 🛠️ Technology Stack
* **Python** (Logic)
* **Folium** (Geospatial Visualization & Mapping)
* **Pandas** (Data Handling)

### 🌍 Key Features
* **Interactive Mapping:** Renders a zoomable map of Riau, Indonesia.
* **Condition Logic:** Automatically color-codes blocks based on health status:
    * 🟢 **Green:** Healthy (NDVI > 0.6)
    * 🟠 **Orange:** Stressed (NDVI 0.4 - 0.6)
    * 🔴 **Red:** Critical/Deforested (NDVI < 0.4)

### 🚀 Usage
```python
# Generates the HTML map file
python map_monitor.py
