# Learning Structure–Dynamics Relationships in Metallic Glasses from Atomic Configurations Using Machine Learning and DeepSets

This repository contains the part of the dataset, source code, and pretrained models used in the study **"Learning Structure–Dynamics Relationships in Metallic Glasses from Atomic Configurations Using Machine Learning and DeepSets."**

The project investigates the prediction of the structural relaxation time ($\log_{10}\tau_{\alpha}$) of metallic glasses from atomic configurations using both conventional machine learning algorithms (KNN, Gradient Boosting, Extra Trees, Random Forest, Decision Tree, and SVR) and the DeepSets neural network.

## Repository Contents

- **ML_model.ipynb** – Training and evaluation of conventional machine learning models.
- **deepsets_with_latent_export.ipynb** – DeepSets training, evaluation, and latent representation export.
- **ml_features.csv** – Structural descriptors used for conventional machine learning.
- **nn_metadata_with_cache.csv** – Metadata for DeepSets training.
- **final_deepsets_cfg_plus_temperature.pt** – Pretrained DeepSets model.
- **final_deepsets_cfg_plus_temperature_with_latent.pt** – Pretrained DeepSets model with latent feature extraction.

## Requirements

Python 3.10+, PyTorch, NumPy, Pandas, scikit-learn, SciPy, and Matplotlib.


