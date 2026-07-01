# House Price Prediction

## Overview
This project focuses on predicting house prices using Machine Learning techniques. The dataset contains various housing attributes such as area, bedrooms, bathrooms, stories, parking facilities, furnishing status, and other property-related features. The goal is to build predictive models that can accurately estimate house prices based on these features.

## Dataset Information
The dataset contains:

- Total Records: 545
- Total Features: 13

### Features
- Price
- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road Access
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading
- Imported the housing dataset using Pandas.
- Loaded data from `Housing.csv`.

### 2. Data Exploration
- Displayed the first 10 records of the dataset.
- Examined dataset dimensions and structure.
- Identified available features and target variable.

### 3. Data Preprocessing
- Prepared the dataset for machine learning.
- Handled categorical features for model training.
- Organized data into input features and target variable.

### 4. Model Development
Implemented machine learning models for house price prediction:

- Linear Regression
- Random Forest Regression

### 5. Model Evaluation
Evaluated model performance using regression metrics to compare prediction accuracy and effectiveness.

## Sample Output

Dataset Shape:

```python
(545, 13)
```

Example features include:

```text
price, area, bedrooms, bathrooms, stories,
mainroad, guestroom, basement,
hotwaterheating, airconditioning,
parking, prefarea, furnishingstatus
```

## Applications

- Real Estate Price Estimation
- Property Valuation
- Housing Market Analysis
- Investment Decision Support

## Future Improvements

- Feature Engineering
- Hyperparameter Tuning
- Advanced Ensemble Models
- Deployment as a Web Application

