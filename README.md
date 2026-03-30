# NDVI Time Series Analysis – Kinshasa, DRC

## Overview
Monitoring vegetation dynamics is essential for understanding environmental changes and land use patterns. This project analyzes **Normalized Difference Vegetation Index (NDVI)** time series to assess vegetation health and seasonal variations in different land cover types in Kinshasa, Democratic Republic of Congo. 

The study focuses on three land cover classes: **forest**, **cropland**, and **urban areas** for the year **2022**. Sentinel-2 satellite data processed via **openEO** is used to calculate monthly mean NDVI values for each class.

---

## Objectives
- Compare vegetation dynamics across different land cover types.  
- Analyze seasonal patterns of NDVI in a tropical environment.  
- Provide insights into land cover characterization and environmental monitoring.

---

## Data and Methods
- **Satellite Data**: Sentinel-2 imagery for the year 2022.  
- **Processing**: Monthly mean NDVI values calculated for forest, cropland, and urban polygons.  
- **Tools**: openEO, Python, Jupyter Notebook.  

**Workflow**:
1. Import and preprocess Sentinel-2 imagery.  
2. Mask clouds and unwanted pixels.  
3. Extract NDVI values for each land cover polygon.  
4. Compute monthly mean NDVI for each land cover class.  
5. Visualize and analyze temporal trends.

---

## Results
- **Cropland** shows the highest NDVI values (max ~0.38 in March).  
- **Forest** exhibits moderate NDVI (~0.25 peaks).  
- **Urban areas** have consistently low NDVI values (~0 or slightly negative).  
- NDVI variations reflect the **seasonal climate** of Kinshasa:
  - Higher NDVI during active growth periods (Jan–Mar).  
  - Declines during rainy season or due to harvesting (Apr–May).  
  - Lowest values during the dry season (July).  
  - Recovery observed Aug–Sep due to regrowth or clearer observations.  

**Limitations**:
- Cloud contamination may still affect NDVI despite cloud masking.  
- NDVI saturation in dense forest areas may reduce sensitivity.  
- Sentinel-2 spatial resolution may not capture fine-scale heterogeneity.

---

## Conclusion
NDVI time series effectively distinguish land cover types and monitor vegetation dynamics over time. This analysis demonstrates seasonal patterns influenced by climatic conditions and highlights the potential of satellite data for tropical environmental monitoring.

---

## How to Use
1. Open the notebook: `NDVI_timeseries_analysis.ipynb` in Jupyter or [Google Colab](https://colab.research.google.com/).  
2. Run the notebook cells to reproduce the NDVI calculations and visualizations.  
3. Optional: Export results to HTML or Markdown for sharing.

---

## Repository Contents
- `NDVI_timeseries_analysis.ipynb` – Jupyter Notebook with code, figures, and analysis.  
- `NDVI_timeseries_analysis.html` – Exported HTML version for easy viewing.  
- `README.md` – Project description and instructions.  

---

## Author
**Kandjale Yolima Espérance** – Master Student in Earth Observation and Geoanalysis of the Living Environment

