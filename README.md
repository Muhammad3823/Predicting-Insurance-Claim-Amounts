Objective

Predict medical insurance charges using a Linear Regression model and understand the dataset through basic exploration and preprocessing.

Approach
1. Data Loading

Imported essential libraries: pandas, numpy, matplotlib, and sklearn modules.

Loaded the dataset (insurance.csv) into a DataFrame.

Displayed dataset shape and initial overview.

2. Data Exploration & Preprocessing

Checked dataset structure, columns, and values.

Handled categorical variables (such as sex, smoker, region) using encoding.

Performed train–test split to prepare data for modeling.

3. Model Training

Trained a Linear Regression model on the processed dataset.

Used training data (X_train, y_train) to fit the model.

4. Predictions & Evaluation

Made predictions on the test dataset (X_test).

Evaluated model performance using:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

Results & Insights

Linear Regression successfully predicted insurance charges based on provided features.

MAE and RMSE indicate how closely predictions matched actual values.

Model performance can be improved further with:

Feature scaling

Polynomial features

Trying more complex models (Random Forest, XGBoost)
