# Group Project — Data Preparation (Two Original Datasets)

This repository contains the **dataset portion** of our classification project using two original (non-Kaggle/UCI/HF) datasets collected directly from official city open-data portals.

## Datasets
1. **NYC Yellow Taxi Trips (2023 sample)**
   - Source: NYC Taxi & Limousine Commission (TLC), NYC Open Data
   - Task: Classify **high tips (≥20%)**

2. **Chicago Food Inspections (sample)**
   - Source: City of Chicago, Department of Public Health
   - Task: Classify **Pass vs Not-Pass**

## What’s Included
- **Notebook**: `Datasets_Prep_Notebook_with_Ethics.ipynb`
- **Outputs** (placeholders in /data directory, real files generated when running the notebook):
  - `taxi_raw_2023.csv`, `taxi_clean_features.csv`
  - `chi_food_raw.csv`, `chi_food_clean_features.csv`

⚠️ **Note:** The CSV files in this repo are **placeholders** (headers only).  
To generate full data, run the notebook — it will download fresh samples via the official APIs.

## Ethics
These datasets are de-identified public records. We use aggregated encodings to mitigate privacy risk and avoid stigmatizing individuals, neighborhoods, or businesses.
