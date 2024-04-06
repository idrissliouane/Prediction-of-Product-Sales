# Prediction of Product Sales
**Author:IDRISS LIOUANE**
## Business problem:
The  project will be a sales prediction for food items sold at various stores. The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.
# Methods
.**Data preparation steps**
- 1. Missing Data Handling
Missing values in the dataset were imputed using SimpleImputer with the strategy (median and constant) for numerical/categorical features, respectively.
Any remaining missing data points were dropped from the dataset, as they constituted a small fraction of the total observations.
- 2. Feature Engineering.
Categorical variables were encoded using one-hot encoding  and numerical feature were scaled using StandardScaler to prepare them for modeling
- 3. Train-Test Split
The dataset was divided into training and testing sets using a 75-25 split.
- 4. Model Selection and Training
Several machine learning algorithms, including linear regression and random forest were trained on the training data.
Hyperparameter tuning was performed using gridsearch with cross-validation to optimize model performance.
The best-performing model based on evaluation metrics was selected for final deployment.
# Results
![heatmap](https://github.com/idrissliouane/Prediction-of-Product-Sales/assets/156426629/9a17fb5d-260c-4ebc-abcb-3e05e6189581)

**Model**

Model Evaluation Metrics
Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R^2) were used as evaluation metrics to assess model performance.
Model Performance
The selected model achieved an MAE of 737.202, RMSE of 1,062.369, and R^2 of 0.591 on the test dataset.
