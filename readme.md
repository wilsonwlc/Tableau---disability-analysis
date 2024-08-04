# Tableau: Disability Analysis in England and Wales, 2011

## Description
* This project analyses disability statistics from the 2011 Census for England and Wales. The dataset provides age-standardised percentages of usual residents by long-term health problems or disabilities, sex, and age as of Census Day, 27 March 2011.

## Datasets
1. **Disability in England and Wales, 2011**: The dataset `disabilitycensus2011.xlsx` can be from [Office for National Statistic (ONS)](https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/disability/datasets/disabilityinenglandandwales2011). It classifies usual residents by long-term health problems or disabilities, sex, and age. 
2. **Local Authority Districts (May 2024) Boundaries UK BFC**: The data `Local_Authority_Districts_May_2024_Boundaries_UK_BFC_8443829521533055349.geojson` can be downloaded from [Open Geography portal](https://geoportal.statistics.gov.uk/datasets/f23beaa3769a4488b6a5f0cfb7980f51_0/explore). It provides geographical boundaries for local authority districts

## Data Preparation
* The dataset was prepared using R, as documented in `data_preparation.ipynb`

## Analysis
* The analysis was conducted using Tableau (`analysis.twb`) with the following steps:
    * **Overall Disability**: Analysed the age-standardised percentage of overall disability.
    * **Disability Severity**: Drilled down to analyse the age-standardised percentages of slight disability and severe disability.
    * **Disability Status and Gender**: Further analysis by disability status (slight vs severe) and by gender (female vs male).

## Requirements
* R with the following packages: `readxl`, `dplyr`, `stringr`, `sf`, `ggplot2`.
* Tableau