# GB1 Protein Fitness Prediction

**CS512 – Machine Learning | Sabancı University**

## Project Overview

This project aims to predict the experimentally measured fitness of GB1 protein variants using machine learning. We investigate whether incorporating amino acid biochemical properties improves prediction performance compared with sequence-based representations alone.

## Dataset

We use the **GB1 dataset** from the Fitness Landscape Inference for Proteins (FLIP) benchmark, containing 8,733 protein variants with experimentally measured fitness scores.

## Feature Representations

- **Sequence-only:** One-hot encoding of four variable amino acid positions (80 features).
- **Sequence + Biochemical:** One-hot encoding combined with hydrophobicity, charge, amino acid volume, and mutation count (93 features).

## Machine Learning Models

- Ridge Regression
- XGBoost Regressor
- Neural Network (NN)

## Evaluation Metrics

Model performance will be evaluated using MAE, RMSE, R², and Spearman correlation.

## Project Status

🚧 Work in progress.

## Team Members

- Hossein Moein
- Merve Kaftan
- Özge Nur Öztürk
