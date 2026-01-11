# 🌲 Forest Fire Prediction – Data Mining Project (USTHB M2 SII 2025/2026)

This project aims to develop a predictive model for forest fires in Algeria and Tunisia using climate, soil, and elevation data.

## 📊 Steps
1. **Data Analysis & Preprocessing**
   - Exploratory Data Analysis (EDA)
   - Loading and Merging the datasets
   - Data cleaning, integration, and feature engineering
3. **Supervised Learning**
   - KNN, Decision Tree, and Random Forest (from scratch + Scikit-learn comparison)
4. **Unsupervised Learning**
   - K-Means, DBSCAN, and CLARANS (from scratch + Scikit-learn comparison)

## 📁 Dataset Sources
- [NASA FIRMS – Fire Data](https://firms.modaps.eosdis.nasa.gov/country/)
- [FAO – Land Cover](https://data.apps.fao.org/catalog/iso/0e958049-2a0a-4935-83c8-af78626068fc)
- [WorldClim – Climate Data](https://worldclim.org/data/monthlywth.html)
- [USGS – Elevation Data](https://edcintl.cr.usgs.gov/downloads/sciweb1/shared/topo/downloads/GMTED/Grid_ZipFiles/be15_grd.zip)
- [FAO – Soil Data](https://www.fao.org/soils-portal/data-hub/soil-maps-and-databases/harmonized-world-soil-database-v20/en/)

## ⚙️ Tech Stack
- Python (Pandas, NumPy, Matplotlib, Scikit-learn)
- Jupyter Notebook
- Git & GitHub for version control
- geopandas, rasterio (for spatial raster processing)

## 📂 Repository structure
```
/README.md
/data/              # raw and processed datasets (large files excluded from git so it contains only the final ready to use dataset)
/notebooks/         # Jupyter notebooks for each step of the process (Loading, EDA, Merging, Preprocessing and feature engeneering, Modeling, Evaluation)
/models/            # models for supervised and unsupervised (both from scratch and sklearn models)
/results/           # csv files for the results of models
/output/            # diffrent graphs and figures generated along the project
```

---

## 👥 Authors
- **BOULAHLIB Ali** 
- **BENSEMMANE Riad** 
