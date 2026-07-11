# Flood-Susceptibility-Analysis
![Flood Susceptibility Map](./maps/Flood%20Susceptibility%20Index%20of%20Jabalpur.png)
GIS-based Flood Susceptibility Mapping using QGIS and Multi-Criteria Decision Analysis (MCDA)

##  Project Summary

| Item | Details |
|------|---------|
| Project Type | GIS & Remote Sensing |
| Study Area | Jabalpur District, Madhya Pradesh |
| Software | QGIS |
| Analysis | Multi-Criteria Decision Analysis (MCDA) |
| Technique | Weighted Overlay |
| Output | Flood Susceptibility Map |

##  Project Overview

Floods are among the most common natural hazards, causing significant impacts on human settlements, agriculture, and infrastructure. This project identifies flood-prone areas by integrating multiple environmental factors using GIS-based Multi-Criteria Decision Analysis (MCDA).

The final output is a flood susceptibility map that classifies the study area into different flood susceptibility zones, providing valuable information for disaster risk management and land-use planning.

##  Objectives

- Identify flood-prone areas within the study area.
- Integrate multiple spatial datasets using Weighted Overlay Analysis.
- Demonstrate the application of GIS in disaster risk assessment.
- Produce a flood susceptibility map to support planning and decision-making.

##  Study Area

The study was conducted for **Jabalpur District, Madhya Pradesh, India**. The district experiences seasonal rainfall and contains a diverse landscape of urban areas, agricultural land, forests, rivers, and drainage networks. These varying physical characteristics make it suitable for flood susceptibility assessment using GIS-based spatial analysis.

##  Datasets Used

| Dataset | Purpose |
|----------|---------|
| Digital Elevation Model (DEM) | Elevation and terrain analysis |
| Land Use/Land Cover (LULC) | Surface characteristics |
| Rainfall | Rainfall distribution |
| Drainage Network | Proximity to rivers and streams |
| Administrative Boundary | Clipping and study area boundary |

##  Software Used

- QGIS
- QGIS Processing Toolbox

##  Methodology

The flood susceptibility map was developed using a Multi-Criteria Decision Analysis (MCDA) approach with Weighted Overlay Analysis.

The workflow included:

1. Collection of spatial datasets.
2. Data preprocessing and clipping to the Jabalpur district boundary.
3. Preparation of thematic layers:
   - DEM
   - Land Use/Land Cover (LULC)
   - Rainfall
   - Drainage Network
4. Reclassification of each thematic layer based on flood susceptibility.
5. Assignment of weights to each factor according to its influence on flooding.
6. Weighted Overlay Analysis to generate the final Flood Susceptibility Map.
7. Classification of flood susceptibility into different risk zones.

##  Workflow

The project followed the workflow shown below:

Data Collection

↓

Data Preprocessing

↓

Preparation of Thematic Layers

↓

Raster Reclassification

↓

Weight Assignment

↓

Weighted Overlay Analysis

↓

Flood Susceptibility Map

↓

Map Layout & Visualization

##  QGIS Processing Tools Used

The following QGIS tools were used during the analysis:

- Clip Raster by Mask Layer
- Reclassify by Table
- Raster Calculator
- Weighted Overlay
- Merge Layers
- Extract by Mask
- Layout Manager

##  Results

The analysis produced a Flood Susceptibility Map for Jabalpur District, classifying the study area into different flood susceptibility zones ranging from **Very Low** to **Very High**.

The map highlights areas that are more vulnerable to flooding and can support disaster management, land-use planning, and infrastructure development.

##  Skills Demonstrated

- GIS Analysis
- Raster Analysis
- Weighted Overlay Analysis
- Multi-Criteria Decision Analysis (MCDA)
- Hydrological Analysis
- Data Preprocessing
- Cartographic Map Design
- Spatial Decision Support

##  Future Improvements

- Incorporate additional flood-related factors such as soil type.
- Automate the workflow using Python.
- Perform validation using historical flood records.
- Extend the analysis using PostGIS and spatial SQL.

## 📚 Data Sources

- SRTM Digital Elevation Model (DEM)
- OpenStreetMap (Drainage Network)
- Land Use/Land Cover (LULC)
- Rainfall Data
- Administrative Boundary of Jabalpur District

*Datasets were obtained from publicly available sources for education purposes.*
