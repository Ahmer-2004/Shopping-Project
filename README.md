# Online Shopping Purchase Prediction

Machine learning project for predicting whether an online shopping session results in a purchase using customer browsing behavior.

# Overview

This project uses the Online Shoppers Purchasing Intention dataset to perform binary classification and compare multiple machine learning models.

# Models

K-Nearest Neighbors

Gaussian Naive Bayes

Logistic Regression

Random Forest

Neural Network

Best Result

Random Forest achieved the best reported accuracy of approximately 90.26%.

# Dataset

The dataset contains 12,330 online shopping sessions with 17 input features and a binary Revenue target indicating whether a purchase was made.

Dataset: UCI Online Shoppers Purchasing Intention Dataset

# Technologies

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

# Project Structure

Shopping-Project/
├── Project_shopping.ipynb
├── README.md
└── .gitattributes

# Setup

git clone https://github.com/<your-username>/Shopping-Project.git
cd Shopping-Project
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook

Download the dataset from UCI and place it in the project directory before running the notebook.

# Future Improvements

Feature engineering

Hyperparameter tuning

Cross-validation

Class imbalance handling

Model explainability

Deployment through an API
