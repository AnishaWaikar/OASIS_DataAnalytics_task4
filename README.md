# OASIS_DataAnalytics_task4
🏠 Task 4 — House Price Prediction Using Linear Regression

🎯 Objective

To develop a baseline regression model capable of predicting house prices from structured property attributes. The focus was on preprocessing categorical features, training a linear regression model, and evaluating prediction accuracy using standard regression metrics.

📝 Steps Performed

Data Loading & Review
Imported the housing dataset, checked statistical summary, and verified absence of missing values.

Feature Selection & Encoding
Separated predictors from the target (price).
Identified categorical attributes and applied one-hot encoding using ColumnTransformer to convert them into numerical features.

Data Splitting
Partitioned the encoded dataset into training and testing sets (80/20 split) using train_test_split to ensure unbiased evaluation.

Model Training
Trained a Linear Regression model on the transformed training set to establish a baseline predictive model.

Model Evaluation
Generated predictions on the test split and evaluated model performance using:

R² Score to measure variance explained

RMSE to capture typical prediction error

MAE to quantify absolute deviation from actual values

Result Visualization
Plotted predicted vs actual prices to visually assess alignment and residual behavior.

🛠 Tools Used

Python Libraries: Pandas, NumPy, Scikit-learn

Preprocessing: One-Hot Encoding, Train-Test Split

Modeling: Linear Regression

Metrics: R², RMSE, MAE

Visualization: Matplotlib

📌 Outcome

The model produced reasonable baseline predictions of house prices, with evaluation metrics indicating how well linear relationships captured price variation. The workflow established a foundation for future improvements through feature engineering, regularization methods, and comparative model experimentation.
