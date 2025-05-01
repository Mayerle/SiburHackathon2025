# Predicting Molecular Lipophilicity (LogP) Using a GNN and SVR
## Description
This repository contains our team’s solution for the <b>Element 119</b> competition organized by <b>SIBUR</b>, focusing on the application of artificial intelligence in chemistry.
The goal of the project is to predict the lipophilicity coefficient (LogP) of organic molecules using an ensemble of two models:

- Graph Neural Network (GNN) implemented with PyTorch for analyzing molecular structures<br>
- Support Vector Regression (SVR) with engineered physicochemical features

## Key features
- Data Preprocessing: Conversion of SMILES to molecular graphs (for GNN) and RDKit descriptors (for SVR)
- Validation: Nested cross-validation and testing on blind datasets

## Results
- Top 20 in the final leaderboard
- Public dataset RMSE: 0.64311
- Private dataset RMSE: 0.72190