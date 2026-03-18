# LULC-AT: Land Surface Water Mapping Using Sentinel-1 SAR and Land Cover-Based Adaptive Thresholding

This repository provides the scripts used for LULC-AT, a land surface water detection framework that combines Sentinel-1 SAR VV and VH backscatter with land use/land cover (LULC) information from ESA WorldCover.
The approach was developed to improve surface water mapping in tropical environments, where optical satellite observations are often limited by persistent cloud cover.

# Overview

- **Method**: LULC-AT (Land Use/Land Cover-Based Adaptive Thresholding)
- **Satellite data**: Sentinel-1 SAR
- **LULC data**: ESA WorldCover
- **Target region**: Tropical regions
- **Key case study**: Bangladesh
- **Temporal scale**: Monthly analysis (2021)
- **Key Features**:
  - Surface water detection using Sentinel-1 VV and VH backscatter
  - LULC-specific optimal thresholds to account for spatial heterogeneity
  - Evaluation of six formulae derived from VV and VH combinations
  - Applicability to cloud-prone and flood-affected tropical regions
