# Unsupervised Learning for EO Data Classification

![Cluster Visualization](https://via.placeholder.com/800x400.png?text=Cluster+Visualization)

This repository demonstrates unsupervised learning techniques (K-means and GMM) for classifying sea ice and leads in Sentinel-2/3 satellite data. Developed for educational and research purposes in Earth Observation (EO) analysis.

## Table of Contents
- [Features](#features)
- [Environment Setup](#environment-setup)
- [Data Preparation](#data-preparation)
- [Quick Start](#quick-start)
- [Code Structure](#code-structure)
- [Model Training](#model-training)
- [Visualization](#visualization)
- [References](#references)
- [License](#license)

## Features
- **K-means Clustering** implementation for optical data
- **Gaussian Mixture Models (GMM)** for altimetry data
- Sentinel-2 image processing pipeline
- Waveform analysis for SAR data
- Performance evaluation metrics

## Environment Setup
```bash
# Google Colab
!pip install rasterio netCDF4 scikit-learn matplotlib numpy

# Local environment
conda create -n eo-clustering python=3.8
conda install -c conda-forge rasterio netCDF4 scikit-learn matplotlib numpy
