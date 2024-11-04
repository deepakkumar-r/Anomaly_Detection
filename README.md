# Anomaly Detection in UCI Heart Disease Dataset

This project focuses on anomaly detection in a medical dataset to identify potential outliers in heart disease data. Various methods, including statistical and machine learning approaches, were implemented to detect anomalies in the data. The project follows a structured approach, from data preprocessing to evaluation, to ensure accurate anomaly detection.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Methods](#methods)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [Future Improvements](#future-improvements)
8. [License](#license)

## Project Overview
The objective of this project is to apply anomaly detection techniques to identify irregularities in the UCI Heart Disease dataset. Anomalies in medical data can indicate errors or unique cases that may require further investigation, and identifying these anomalies is essential for quality data analysis.

## Dataset
- Dataset Used: [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- Attributes: The dataset includes various features such as `age`, `sex`, `trestbps` (resting blood pressure), `chol` (cholesterol level), `thalach` (maximum heart rate achieved), and `oldpeak` (ST depression induced by exercise relative to rest).
- Target Variable: 'num' (presence of heart disease, encoded as 1 if present and 0 if absent)

## Methods
The project implements the following anomaly detection techniques:
1. **Z-Score** - Simple statistical method based on standard deviations.
2. **Mahalanobis Distance** - Multivariate distance-based approach.
3. **Local Outlier Factor (LOF)** - Density-based local outlier detection.
4. **One-Class SVM** - Support vector method for anomaly detection.
5. **Isolation Forest** - Tree-based method for isolating anomalies.

Each method evaluates the dataset for anomalies based on different criteria, providing unique insights into potential outliers.

## Installation
### Prerequisites
This project requires Python 3.6 or later. Ensure that you have the necessary libraries installed.

### Required Libraries
Install the required libraries by running:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy
