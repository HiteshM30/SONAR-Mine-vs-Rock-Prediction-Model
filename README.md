
# SONAR Mine vs Rock Prediction Model

This repository contains a machine learning model that predicts whether sonar signals reflect off a mine or a rock. The model is trained on the well-known SONAR dataset and employs Logistic Regression to make binary classifications based on sonar frequency patterns.




## Overview
Sonar technology is commonly used in underwater exploration, where it's essential to differentiate between metallic objects, such as mines, and natural seabed formations, like rocks. This project aims to provide a solution by applying logistic regression to classify sonar returns accurately.
## Dataset
The dataset, originally from the UCI Machine Learning Repository, includes 208 samples with 60 frequency-based attributes. Each sample is labeled as either Mine (M) or Rock (R) based on the sonar returns.
## Features

- 60 attributes: Frequency response values ranging from 0 to 1.
- Labels: Binary - M (Mine) or R (Rock)


## Model
Logistic Regression
The logistic regression model was selected for this classification task because:

- It’s effective for binary classification problems.
- It's interpretable and provides probabilistic output, allowing confidence assessment for each prediction.
The model learns to classify based on the relationship between the sonar frequency patterns and the object type.
## Dependencies
To install the required libraries, run:
```console
pip install -r requirements.txt
```
Primary Libraries Used:

- scikit-learn: Model training and evaluation
- pandas: Data handling and manipulation
- numpy: Storing the input file
## Project Structure
```
├── data/               # Directory for the sonar dataset
├── main.ipynb          # Jupyter notebook for exploratory data analysis and model training
├── requirements.txt    # Required Python libraries
└── README.md           # Project overview and instructions
```
## Results
The logistic regression model achieved high accuracy, making it suitable for practical use in differentiating mines from rocks. Model evaluation metrics can be visualized in the ```main.ipynb``` file.