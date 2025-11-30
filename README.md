# BSc Thesis – Vendace Habitat Analysis During Summer Stratification

This repository contains the programming part of my BSc thesis project in Bioscience at the University of Skövde.  
The project analysed **vendace (Coregonus albula) habitat** during summer stratification, focusing on the period when habitat volume was at its lowest across a five‑year dataset.

## 🎯 Project Aim
The aim of this project was to **calculate and visualise vendace habitat** during the most stressed measuring occasion over a five‑year period, when oxygen and temperature conditions limited available habitat volume.

## 📂 Repository Contents
- `README.md` – Overview of the project  
- `Clean_and_qualitycheck_BCs/` – R code for quality checking and cleaning SLU environmental monitoring data  
- `Functions_BCs/` – R functions for splitting cleaned data into station/date data frames, looping through them, and plotting oxygen/temperature profiles with habitat boundaries  
- `Analysis_BCs/` – Scripts for running analyses using the functions above  
- `Photoshop_and_QGIS_Workflow_BCs/` – PDF documenting the complete workflow with function input/output in Photoshop and QGIS  
- `QGIS_Reclassify_Görveln_BCs/` – QGIS code for reclassifying depth DEMs at station Görveln  
- `QGIS_Reclassify_Skarven_BCS/` – QGIS code for reclassifying depth DEMs at station Skarven  

## 🔧 Methods
- Data cleaning: indexing, NA clearing, and error/outlier detection in SLU monitoring datasets  
- Function development: automated splitting of datasets, plotting of oxygen/temperature profiles, and calculation of habitat thickness  
- GIS analysis: raster reclassification in QGIS to assign habitat thickness values to depth DEMs  
- Workflow documentation: integration of R analysis with QGIS and Photoshop for visualisation  

## ⚠️ Note
The code in this repository was developed specifically for the thesis and served as the basis for examination.

## 🎓 Context
Developed as part of my BSc thesis in Bioscience at the University of Skövde, with a focus on aquatic ecology and habitat modelling.

