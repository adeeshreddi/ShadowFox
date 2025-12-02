ShadowFox — Boston House Price Prediction

I built this project to predict Boston house prices using a regression model.
The dataset includes features like the number of rooms, crime rate, nitrogen oxide levels, distance to work areas, and other factors that influence how house values change across different parts of Boston.

🔍 What I Did

I followed a complete ML workflow so the model could learn properly and make reliable predictions.
Here’s what I covered:

1. Data Preprocessing
	•	Filled missing values
	•	Scaled numerical features
	•	Encoded categorical features
	•	Used a ColumnTransformer to keep everything clean and consistent

2. Model Selection

To compare how different regression techniques perform, I trained three basic models:
	•	Linear Regression
	•	Ridge Regression
	•	Lasso Regression

These gave me a clear picture of how regularization affects performance.

3. Model Training

I used an 80/20 train-test split and trained each model using a single pipeline so preprocessing and training happened together.

4. Evaluation

For each model, I calculated:
	•	RMSE
	•	MAE
	•	R² Score

I also plotted Actual vs Predicted values to visually check how well the model performs.
After comparing all three, I selected the best one based on the lowest RMSE.

📁 Files Included
	•	ShadowFax_1.ipynb — My full notebook with all steps
	•	HousingData.csv — The dataset I used

🚀 How to Run It

Just open the notebook in Google Colab or Jupyter Notebook and run it from top to bottom.
