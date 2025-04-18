# 🛒 Rossmann Store Sales Prediction - Kaggle Competition

This repository contains code and data used to develop a deep learning model for forecasting daily sales across 1,115 Rossmann drug stores in Germany. The project was submitted to the Rossmann Store Sales Kaggle competition.

## 👥 Team Project
This was a collaborative effort as part of a team competition. I contributed to:
- Preprocessing and cleaning large datasets
- Engineering time-based and categorical features
- Implementing and optimizing a deep learning model using TensorFlow/PyTorch
- Fine-tuning hyperparameters to enhance model performance

## 🧪 Tools & Technologies
- Python
- Pandas, NumPy
- TensorFlow / PyTorch
- Scikit-learn
- Data visualization

## 📁 Files Included
- `rossmann_model.py`: Neural network model for predicting daily sales
- `data/`: Contains CSV files used for training and evaluation
    - `train.csv`
    - `test.csv`
    - `store.csv`
    - `sample_submission.csv`
- README.md: Documentation

## 🧠 Model Summary
The model takes various inputs including:
- Categorical store-specific information (e.g. store type, assortment)
- Temporal features extracted from dates (e.g. day of week, month, holiday flags)
- Promotion indicators

We experimented with several architectures, loss functions, and learning rates. Final performance achieved a mean squared log error (MSLE) of 0.35, with the top-scoring solution on the leaderboard reaching 0.10021.

## 📊 Dataset Description
- `train.csv`: Historical sales data for each store (with date, sales, customers, open status)
- `test.csv`: Data to generate predictions for
- `store.csv`: Metadata about each store (type, competition, promo details)
- `sample_submission.csv`: Format for submission to Kaggle

## IMPORTANT
*Due to the collaborative nature of this project, only code and components I directly worked on are included.*

---
