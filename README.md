# Optimizing Lead Time Prediction in Healthcare Supply Chain Management Using Machine Learning

This project focuses on developing a predictive model to optimize healthcare supply chain processes, with a specific emphasis on lead time prediction. The model leverages machine learning techniques to analyze factors affecting supply chain efficiency during normal and pandemic periods.

## Overview
Efficient supply chain management is crucial in healthcare, where delays can have life-critical consequences. This project uses the USAID GHSC-PSM Health Commodity Delivery Dataset to build a machine learning model that predicts lead times and identifies key contributing factors.

### Key Highlights
- Achieved a median error of approximately **7 days** using Random Forest regression.
- Analyzed feature importance during normal operations and pandemic periods.
- Explored the effects of COVID-19 on healthcare supply chain dynamics.

## Dataset
The dataset includes detailed records of healthcare commodity deliveries from **2015 to 2025** under various USAID initiatives. Preprocessing steps reduced the dataset to **16,000 rows** with selected features.

## Usage
The project contains several notebooks, but only a few are essential:

- **`GeneralizedRandomForestModel.ipynb`**: The final model used in the paper.
- **`DataReadMe.pdf`**: Documentation detailing the purpose of each feature.
- **`dataCleaning.ipynb`**: Describes the preprocessing steps applied to the dataset.
