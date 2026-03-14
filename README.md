# Parkinson’s Disease Detection using Speech Data

This project uses machine learning models to detect Parkinson’s disease from speech recordings.

## Dataset
Parkinson's Speech Dataset from the UCI Machine Learning Repository.
Dataset link:
https://archive.ics.uci.edu/dataset/301/parkinson+speech+dataset+with+multiple+types+of+Audio+recordings

## Tasks
1. Binary Classification
   - Healthy vs Parkinson’s

2. Severity Classification
   - Mild Parkinson’s
   - Moderate Parkinson’s

## Models Used
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting

## Dataset Details
- 20 Parkinson’s patients
- 20 healthy individuals
- 1040 speech samples

## Limitations
The dataset does not contain severe Parkinson’s cases, so severity classification includes only mild and moderate categories.

## Files
- `roobroo_with_parkinson_dataset.ipynb"` – data preprocessing
- `binary_class_modeling_parkinson.ipynb` – binary classification
- `Severity_classification_parkinson.ipynb` – severity classification
