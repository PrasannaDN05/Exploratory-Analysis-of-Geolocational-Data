# Exploratory Analysis of Geolocational Data

An end-to-end geospatial data analysis project built with Python to clean, explore, visualize, and identify spatial patterns in latitude-longitude datasets.

The project combines exploratory data analysis, spatial density analysis, temporal analysis, and DBSCAN clustering using Haversine distance to identify geographic clusters and noise points.

---

## Project Overview

Geolocational datasets contain valuable information about where and when events occur. However, raw location data can contain missing values, invalid coordinates, duplicate records, and noisy observations.

This project develops a reusable analysis pipeline for processing location-based data and extracting meaningful spatial patterns.

### Pipeline

```text
Load Data
    ↓
Data Cleaning
    ↓
Summary Statistics
    ↓
Spatial EDA
    ↓
Density Analysis
    ↓
Temporal Analysis
    ↓
DBSCAN Clustering
    ↓
Interactive Map
    ↓
Export Results
