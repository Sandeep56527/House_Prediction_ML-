# House_Prediction_ML-
Project: Housing Price Prediction. This project aimed to predict housing prices using machine learning techniques.
Leveraged advanced regression models to provide accurate real estate price forecasts, assisting buyers, sellers, and investors in data-driven decision-making.
Motivation
Precise housing price prediction is crucial for market stakeholders.
This project eliminates bias by using data-driven insights for real estate valuation.
 

Data Cleaning & Preprocessing
Handling Missing Values:
Identified missing values in columns like FireplaceQu and LotFrontage.
Imputed categorical features with relevant placeholders and handled numerical data accordingly.
Feature Engineering:
Created new features such as TotalSF, HouseAge, RemodelAge, and TotalBathrooms to enhance model accuracy.
Data Transformation:
Applied one-hot encoding for categorical features.
Scaled numerical features to improve model performance.
Data Splitting:
Divided data into 80% training and 20% testing sets for model evaluation.
Model Training & Evaluation
Linear Regression: Baseline model with RMSE of 29,657.86.
Random Forest: Improved performance with RMSE of 29,552.90.
XGBoost: Achieved RMSE of 27,283.39, capturing complex patterns.
Stacking Ensemble: Combined multiple models, reducing RMSE to 25,633.18.
XGBoost Hyperparameter Tuning: Optimized parameters lowered RMSE to 25,553.10.
Final Model: Tuned XGBoost with best RMSE of 25,419.25, demonstrating superior accuracy.
Key Visualizations & Insights
Correlation Heatmap: Showcased relationships between numerical features.
Feature Importance Graphs: Identified key predictors of housing prices.
Scatter Plots & Analysis:
GrLivArea vs. SalePrice: Strong positive correlation, but some outliers exist.
TotalBsmtSF vs. SalePrice: Larger basements generally increase house prices.
YearBuilt vs. SalePrice: Newer homes tend to have higher sale prices.
GarageArea vs. SalePrice: Larger garages correlate with higher prices.
1stFlrSF vs. SalePrice: Strong price impact for homes with larger first-floor areas.
FullBath vs. SalePrice: Positive impact on house valuation.
OverallQual vs. SalePrice: Significant predictor of pricing trends.
Predicted Housing Prices (Sample Results)
House 1: $139,935.80
House 2: $333,368.47
House 3: $103,031.56
House 4: $162,947.81
House 5: $312,906.88

