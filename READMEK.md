# 🚦 Aggregated & Preprocessed Traffic Data — EDA

This repository contains my **Exploratory Data Analysis (EDA)** and **Data Preprocessing** work for a traffic congestion dataset.  
The goal of this project is to understand traffic flow dynamics, analyze temporal and spatial patterns, and prepare the dataset for predictive modeling.

## Files included
- `Aggregated_Preprocessed_Data_Karthik.ipynb` — full notebook: loading, cleaning, aggregation, feature engineering, EDA, and baseline modeling examples.
- `aggregated_preprocessed_rawfeatures.csv` *(optional)* — exported aggregated dataset with engineered features.
- `aggregated_preprocessed_scaled.csv` *(optional)* — scaled numeric dataset ready for modeling.
- `Effect_of_Traffic_on_Uber_Karthik.pdf` — one-page research report on how traffic affects Uber pricing.
- `EDA_Modeling_Summary_Karthik.pdf` — short presentation summarizing approach and next steps.

## Summary
This project aggregates traffic sensor counts to hourly intervals per junction, creates time-based and lag features, merges event/weather data (if available), and prepares datasets for forecasting hourly traffic volumes. Models used include baseline persistence, RandomForest, and LightGBM (recommended).

## How to run
1. Open `Aggregated_Preprocessed_Data_Karthik.ipynb` in Jupyter or GitHub.
2. Install dependencies: `pip install pandas numpy matplotlib scikit-learn`
3. Update `CONFIG` cell at top of the notebook to match your local filenames and columns.
4. Run all notebook cells to reproduce results and export CSVs.

Author: Karthik  
