# 🛰️ Land Cover Classification – Central Chhattisgarh (Google Earth Engine)

## 🔹 Project Overview
This project performs land cover classification for the Central Chhattisgarh region using Landsat 8 Surface Reflectance imagery within the Google Earth Engine (Python API). Both unsupervised and supervised approaches were implemented to generate thematic land cover maps and examine label-free and labeled machine learning workflows.

---

## 🔹 Data Preparation
Multispectral Landsat 8 bands were radiometrically scaled to normalize reflectance values. Pixel samples were extracted from a defined Area of Interest (AOI) and mapped to spectral bands for clustering and model training.

---

## 🗺️ Unsupervised Classification
A K-Means clustering workflow segmented imagery into five thematic classes:

- Vegetation  
- Forest  
- Water bodies  
- Sandy regions  
- Built-up areas  

Clusters were reclassified, visualized with custom legends, and exported as georeferenced raster outputs, enabling label-free pattern extraction from satellite imagery.

---

## 📊 Supervised Classification
Supervised classification used Google Dynamic World labels as reference data.

Main steps:
- Automatic training sample generation  
- Spectral feature mapping  
- Train-validation split  
- Training of CART and Random Forest classifiers  
- Visualization and export of classified outputs  

This workflow improved understanding of labeled data creation, feature selection, and classifier training.

---

## 📁 Outputs
The repository includes final classification outputs exported as georeferenced raster datasets.  
Both **unsupervised** and **supervised** classification results are provided as **.tif files** for further GIS and spatial analysis.

---

## Learning Outcomes
- Clustering-based land cover mapping  
- Automated training data creation  
- Feature selection and supervised model training  
- End-to-end classification workflows in Google Earth Engine

---

This project demonstrates practical land cover mapping using both clustering and supervised machine learning techniques in GEE.
