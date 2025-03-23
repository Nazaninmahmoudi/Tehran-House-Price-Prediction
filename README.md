Tehran House Price Prediction (2025)

Project Overview
This project aims to predict house prices in Tehran, Iran, using machine learning models. The dataset includes various features such as area, number of rooms, parking availability, warehouse, elevator presence, and location. By applying different regression models, we identify the best approach for accurate price prediction.

Dataset    
The dataset contains real estate information from Tehran, including house prices in both local currency and USD. It has been preprocessed to ensure data quality and improve model performance.

Models Used          
We experimented with multiple models and fine-tuned hyperparameters to find the most effective predictor:

Linear Regression    
Lasso Regression    
Decision Tree Regressor
Random Forest Regressor
XGBoost Regressor (Best Performing Model)

Key Findings

Area and price have a strong positive correlation—larger houses tend to be more expensive.
Features like elevator presence and address showed little impact on price.
XGBoost Regressor provided the best accuracy with minimal risk of overfitting.

How to Use

Load the dataset into a Kaggle notebook or a local environment.
Run the preprocessing steps to clean and encode the data.
Train the model using the provided code and evaluate performance.
Use the trained model to predict house prices based on user input.

Results & Performance

Train Score: ~0.88
Test Score: ~0.88
Minimal Overfitting: The model generalizes well to unseen data.

Future Improvements

Adding more features such as neighborhood quality, market trends, and economic factors.
Exploring deep learning approaches for further accuracy improvement.
Integrating real-time price updates for dynamic predictions.

Author & Contact
Project by Nazanin Mahmoudy, 2025
📧 Email: Nazaninmahmoudy@gmail.com
🔗 GitHub: https://github.com/Nazaninmahmoudi
