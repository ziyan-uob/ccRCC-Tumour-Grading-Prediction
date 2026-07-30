# Multi-Omics Analysis of Tumour Grade in Clear Cell Renal Cell Carcinoma

## Overview
This repository contains the code and selected results for the MSc dissertation:

**Integrating transcriptomics and proteomics with interpretable machine learning for tumour grading prediction in clear cell renal cell carcinoma**

The project investigates molecular differences between low-grade and high-grade clear cell renal cell carcinoma (ccRCC) using transcriptomic and proteomic data from the CPTAC cohort. Interpretable machine learning models were developed for tumour grade prediction and externally validated using the TCGA-KIRC cohort.

## Repository Structure
ccRCC-Tumour-Grading-Prediction
- data/
   original datasets
- figures/
   Figures used in the dissertation
- results/
   Model outputs and performance results
- ccRCC_Analysis.ipynb
- README.md
- LICENSE

## Workflow
The analysis includes:
1. Data preprocessing
2. Exploratory data analysis (PCA and hierarchical clustering)
3. Differential expression analysis
4. Batch effect correction using ComBat
5. Feature selection
6. Logistic Regression modelling
7. Random Forest modelling
8. External validation using TCGA-KIRC

## Data
The datasets analysed in this study are publicly available.
- CPTAC (Clinical Proteomic Tumor Analysis Consortium)
- TCGA-KIRC (The Cancer Genome Atlas Kidney Renal Clear Cell Carcinoma)

## Software
The analysis was performed using Python.

Main packages include:
- pandas
- numpy
- scipy
- scikit-learn
- statsmodels
- matplotlib
- seaborn
