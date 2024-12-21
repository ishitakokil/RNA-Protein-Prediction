# RNA-Protein-Prediction

## Project Overview
This repository contains the implementation for a machine learning project aimed at predicting protein abundance from RNA (gene expression) data. The project uses advanced single-cell genomics datasets in the Anndata format to train and evaluate models. A Multi-Layer Perceptron (MLP) regression model is employed for the prediction task, achieving an RMSE of 0.35, outperforming baseline and linear models.

## Data Overview
The project utilizes two key datasets:
1. GEX (Gene Expression): Pre-processed RNA data filtered for mitochondrial content, UMI counts per cell, and genes detected per cell.
2. ADT (Protein Abundance): Protein data containing 134 cell surface markers and 6 isotype controls.

The data is stored in Anndata objects, a hierarchical data structure used in single-cell genomics research, facilitating metadata management.


