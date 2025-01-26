# 📊 Visualization of Two Large Datasets (Geospatial & Field Data)
## 🌟 Overview  
This project focuses on visualizing two extensive datasets using Python:  
1. **Geospatial Data**: Earthquake events from 1965–2016.  
2. **Field Data**: Cancer death rates in Morocco and globally from 1990–2016.  

The goal is to leverage visualization techniques to extract insights, highlight patterns, and present the data effectively.  

[📹 Watch the Demo](https://www.youtube.com/watch?v=k-rFz0Z0vHg)  

---

## 🔍 Introduction  
This project visualizes two large datasets to identify patterns and trends:  
- **Geospatial Data**: Focuses on the global distribution and intensity of earthquakes.  
- **Field Data**: Examines cancer death rates in Morocco and globally.  

Using the "What/Why/How" methodology, we describe the datasets, pinpoint tasks, and create meaningful visualizations.  

---

## 🌍 Geospatial Visualization  

### Dataset  
- **Source**: [Earthquake Dataset](https://raw.githubusercontent.com/plotly/datasets/master/earthquakes-23k.csv)  
- **Attributes**:  
  - `Date`: Earthquake event date (MM/DD/YYYY).  
  - `Latitude` & `Longitude`: Geographical coordinates.  
  - `Magnitude`: Earthquake intensity on the Richter scale.  
- **Time Period**: 1965–2016.  

### Visualization and Methodology  
#### What?  
- Display global earthquake data with geographic distribution and intensity.  

#### How?  
- **Map Chart**:  
  - Encoded data using `Latitude` and `Longitude`.  
  - Represented magnitude with color intensity.  
- **Python Libraries**:  
  - Plotly: Interactive, density mapbox visualization.  

#### Why?  
- Identify seismic hotspots and analyze earthquake density and intensity over time.  

---

## 🗺️ Field Visualization  

### Dataset  
- **Source**: Cancer death rates dataset (`cancer.csv`).  
- **Focus**: Morocco (1990–2016).  
- **Attributes**:  
  - `Country`, `Code`, `Year`.  
  - Various cancer types (e.g., liver, kidney, breast, etc.).  

### Visualization and Methodology  
#### What?  
- Analyze cancer death rates across countries and in Morocco specifically.  

#### How?  
- **Visualizations**:  
  - **Map Chart**: Display global cancer rates.  
  - **Horizontal Bar Chart**: Focus on Morocco, comparing cancer rates by type.  
- **Python Libraries**:  
  - Matplotlib: Bar charts.  
  - Geopandas & Plotly: Geospatial and interactive visualizations.  

#### Why?  
- Target: Highlight the most common cancer types for preventive measures.  
- Map Chart: Provide a global overview.  
- Bar Chart: Offer detailed comparison within Morocco.  


