# MetroPT-3 Failure Prediction

This repository contains our notebook for **failure prediction on the MetroPT-3 dataset**, using machine learning techniques for predictive maintenance in metro train systems.

## 🧠 Project Overview

The **MetroPT-3 dataset** contains multivariate time-series sensor data from a train’s Air Production Unit (APU).  
The objective of this project is to **predict potential failures** before they occur, helping optimize maintenance scheduling and reduce operational downtime.

The project workflow includes:
- Data loading and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering and transformation  
- Model training and evaluation  
- Insights and results interpretation  


## 📊 Dataset

- Dataset: [MetroPT-3 (UCI Machine Learning Repository)](https://archive.ics.uci.edu/dataset/791/metropt%2B3%2Bdataset)  
- Description:
  - Contains ~1.5 million sensor readings from real train APU systems  
  - Includes 15 analog and digital sensor features  
  - Collected between February and August 2020  
  - Used for classification and predictive maintenance research


## 🧩 Requirements

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
imbalanced-learn
