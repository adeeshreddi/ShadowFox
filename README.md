# ShadowFox — Boston House Price Prediction

I built this project to predict Boston house prices using a regression model.
The dataset includes features like the number of rooms, crime rate, nitrogen oxide levels, distance to work areas, and other factors that influence how house values change across different parts of Boston.

## 🔍 What I Did

    I followed a complete ML workflow so the model could learn properly and make reliable predictions.
    Here’s what I covered:

## 1. Data Preprocessing
	•	Filled missing values
	•	Scaled numerical features
	•	Encoded categorical features
	•	Used a ColumnTransformer to keep everything clean and consistent

## 2. Model Selection

    To compare how different regression techniques perform, I trained three basic models:
	•	Linear Regression
	•	Ridge Regression
	•	Lasso Regression

    These gave me a clear picture of how regularization affects performance.

## 3. Model Training

    I used an 80/20 train-test split and trained each model using a single pipeline so preprocessing and training happened together.

## 4. Evaluation

    For each model, I calculated:
	•	RMSE
	•	MAE
	•	R² Score

    I also plotted Actual vs Predicted values to visually check how well the model performs.
    After comparing all three, I selected the best one based on the lowest RMSE.

## 📁 Files Included
	•	ShadowFax_1.ipynb — My full notebook with all steps
	•	HousingData.csv — The dataset I used

## 🚀 How to Run It

   Just open the notebook in Google Colab or Jupyter Notebook and run it from top to bottom.

# ShadowFox — Car Selling Price Prediction and Analysis

I built this project to estimate used car selling prices using a regression model. The dataset includes features like fuel type, years of service, showroom price, number of previous owners, kilometers driven, seller type, and transmission. All these help understand how a car’s value changes across different situations.

## 🔍 What I Did

I followed a full ML pipeline so the model learns properly and can give dependable predictions.

### Data Preprocessing
• Loaded and cleaned the dataset  
• Handled missing values  
• Scaled numerical features  
• Encoded categorical features  
• Used a clean preprocessing setup so everything stays consistent  

### Exploratory Analysis
• Looked at distributions and patterns  
• Checked correlations  
• Saved key visualizations for understanding price trends  

### Model Training
I used a train–test split and trained the model inside a single pipeline so preprocessing and training happen together. This keeps the workflow simple and avoids leakage.

### Model Evaluation
For the trained model, I calculated:  
• R² Score  
• RMSE  
• MAE  

I also plotted Actual vs Predicted values to understand how well the model is performing.

### Final Selection
After comparing performance metrics, I chose the best model based on the highest R² and lowest RMSE. I also built a simple prediction function you can use to test your own inputs.

## 📁 Files Included
• ShadowFox_2.ipynb — full notebook with all steps  
• Any saved visualizations generated during the workflow  

## 🚀 How to Run It
Open the notebook in Google Colab or Jupyter Notebook and run it from top to bottom. The final cell includes the prediction function that lets you try custom values.
