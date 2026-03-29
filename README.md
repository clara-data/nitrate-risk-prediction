# Nitrate Risk Prediction in Alberta Well Water

Machine Learning Project | Imbalanced Classification | Environmental Health

## Overview
This project predicts unsafe nitrate levels (>10 mg/L) in domestic well water in Alberta using machine learning models. High nitrate levels pose potential health risks, especially for rural populations relying on private wells.

## Dataset
Source: Alberta Open Government  
The dataset includes routine water chemistry measurements such as pH, hardness, sulfate, and dissolved carbon dioxide.

## Methods
- Logistic Regression (interpretable baseline)
- Multilayer Perceptron (MLP)
- Handling imbalanced data (resampling)
- Evaluation metrics: Precision, Recall, F1-score, ROC AUC

## Results
Logistic Regression performs similarly to or better than the MLP on this dataset, showing that simpler models can be effective for structured environmental data.

## Files
- `notebook.ipynb` — full analysis and modeling workflow
- `final_report.pdf` — detailed project report
- `slides.pdf` — presentation slides

## Data Source
https://open.alberta.ca/opendata/domestic-well-water-quality-in-alberta-routine-chemistry
