# Laptop_price_prediction_model
**Laptop Price Prediction | Capstone Project**

This project aims to predict the prices of laptops based on their specifications using machine learning regression techniques. 
The dataset contains detailed information about laptops, including their brand, processor, RAM, storage type, GPU, and more. 
This is a capstone project built as part of a Data Science certification course.


Dataset Overview
The dataset includes features such as:
- Company (Brand)
- TypeName (Type of Laptop)
- Inches (Screen Size)
- ScreenResolution
- Cpu
- Ram
- Memory (SSD/HDD)
- Gpu
- OpSys (Operating System)
- Price (Target Variable)


Tools & Technologies Used
- Python
- Scikit-learn
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook


Machine Learning Approach
- Data Cleaning & Feature Engineering
  - Extracted key features from CPU, GPU, and Memory columns.
  - Converted RAM and storage to numerical values.
- Data Visualization to understand relationships and distributions.
- Model Building
  - Trained multiple regression models (Linear Regression, Decision Tree, Random Forest, Gradient Boosting).
- Model Evaluation
  - R² Score
  - Cross-validation scores
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)


Final Model Performance
- Best Model: Gradient Boosting Regressor
- R² Score: ~0.78
- Features Importance: CPU brand, SSD size, RAM, and GPU brand were among the top predictors of laptop price.
