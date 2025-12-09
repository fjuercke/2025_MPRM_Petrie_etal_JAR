# 2025_MPRM_Petrie_etal_JAR
Multi-factor, Probabilistic Route Modelling (MPRM) algorithm to generate cost surfaces for use in least-cost analysis. 

This repository contains the data and code for our paper:

> Petrie, Cameron A., Friederike K. Jürcke, Toby C. Wilkinson, Hector A. Orengo (submitted). *Over the hills and far away: modelling mobility and connectivity across the Iranian Plateau in late prehistory (c. 10,000-2000 BC) using multi-factor probabilistic corridors*. 
> Journal of Archaeological Research

[//]: # (> <https://doi.org/xxx/xxx>)

## Contents

This repository contains:

- [MPRM_costsurface](MPRM_costsurface): JavaScript code for implementation in Google Earth Engine (GEE).
- [reservoir_instructions](reservoir_instructions): Instructions for loading the reservoir data into your GEE assets.

## How to run the code in your browser

The code has been developed for implementation in Google Earth Engine (c) by H.A. Orengo, T.C. Wilkinson and F.K. Jürcke. 
To run the code: 
1) Ingest the reservoir data into your GEE assets. Please see the [instructions](reservoir_instructions).
2) Copy the code contained in file [MPRM_costsurface](/code/MPRM_costsurface) into the Google Earth Engine code editor.
3) Adjust line 190 in the code, which calls the reservoir data, to where the reservoir data is in your asset manager. 
4) Press 'Run'. 

All further instructions are contained in the JavaScript Code. 

The code presented here is an iteration of the MPRM model. A version of the algorithm that integrates additional 
factors and convolutions of those factors is under further development, and will be presented 
in a separate paper where the additional parameters are used to consider movement across longer 
distances and different environments and landscapes (Orengo et al. n.d.). The repository can be found here:

https://github.com/horengo/Multitemporal-and-multifactor-probailistic-corridor-networks