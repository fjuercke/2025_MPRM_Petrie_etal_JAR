# 2025_MPRM_Petrie_etal_JAR
Multi-factor, Probabilistic Route Modelling (MPRM) algorithm to generate cost surfaces for use in least-cost analysis. 

This repository contains the data and code for our paper:

> Petrie, Cameron A., Friederike K. Jürcke, Toby C. Wilkinson, Hector A. Orengo (2025). *Over the hills and far away: modelling mobility and connectivity across the Iranian Plateau in late prehistory (c. 10,000-2000 BC) using multi-factor probabilistic corridors*. Journal of Archaeological Research
> <https://doi.org/xxx/xxx>

## Contents

The **analysis** directory contains:

- [:file_folder: code](/code): JavaScript code for implementation in Google Earth Engine (GEE). 
- [:file_folder: data](/data): Link to reservoir data and instructions for ingestion into GEE.

## How to run the code in your browser

The code has been developed for implementation in Google Earth Engine (c) by H.A. Orengo, T.C. Wilkinson and F.K. Jürcke. 
To run the code: 
1) Ingest the reservoir data available at LINK into your GEE assets. [instructions](data/reservoir_instructions)
2) Copy the code contained in file [MPRM_costsurface](/code/MPRM_costsurface) into the Google Earth Engine code editor.
3) Adjust line 188 in the code, which calls the reservoir data, to where the reservoir data is in your asset manager. 
4) Press 'Run'. 

All further instructions are contained in the JavaScript Code. 
