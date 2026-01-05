# Satellite-Imagery-based-Property-Valuation

## Overview
This project predicts property prices using a multimodal regression approach
that combines tabular housing attributes with satellite imagery.

## Data Sources
- Housing attributes dataset
- Sentinel-2 satellite imagery via Sentinel Hub API

## Models
- Tabular-only MLP
- CNN-only (ResNet-18)
- Multimodal late-fusion model (CNN + MLP)

## Evaluation Metrics
- RMSE
- MAE
- R² Score

## How to Run
1. Run data_fetcher.py to download satellite images
2. Run preprocessing.ipynb for EDA
3. Run model_training.ipynb to train models
4. Run evaluation.ipynb for metrics
5. Run prediction_generator.ipynb to generate CSV

## Output
final_predictions.csv containing predicted property prices
