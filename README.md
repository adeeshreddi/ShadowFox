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
# ShadowFox — LSTM Language Model Implementation and Analysis 🧠📜

This project documents the implementation, training, and analysis of a character-level Language Model using an LSTM (Long Short-Term Memory) network built from scratch in PyTorch. The objective is to understand how recurrent neural networks capture context in sequential text data and to analyze their strengths and limitations on small datasets.
Instead of using pre-trained models, this project focuses on fundamentals by training an LSTM on a simple corpus, making the learning process transparent and interpretable.
# 🎯 Objective

-Build a basic language model using LSTM

-Understand short-term vs long-term context handling

-Analyze text generation behavior

-Study how dataset size and sequence length affect performance
# 🧱 Model Overview

Architecture:

Embedding Layer

LSTM Layer

Fully Connected Output Layer

Model Type: Character-level Language Model

Framework: PyTorch

Loss Function: Cross-Entropy Loss

Optimizer: Adam (learning rate = 0.005)

This setup allows the model to predict the next character given a sequence of characters.
# 🧹 Data Preparation

Used a small, hardcoded text corpus

Repeated the corpus to increase effective training size

Built a character vocabulary

Encoded characters as integers

Created sliding window sequences for next-character prediction

Converted data into PyTorch tensors


# 🤖 Model Training

Trained for 200 epochs

Tracked training loss across epochs

Observed steady convergence, indicating effective learning

No overfitting observed due to limited data size

A training loss curve was plotted to visualize convergence behavior 


# ✍️ Text Generation and Exploration

A text generation function was implemented to evaluate model behavior using different prompts and temperature settings.

Observations:

Strong performance on short-term context

Generates coherent phrases similar to training data

Struggles with long-range dependencies

Tends to repeat patterns due to small corpus size

Limited creativity because of character-level modeling

# 🔬 Research Questions Explored

How effectively does the LSTM handle short vs long contexts?

Strong for short sequences, weak for long dependencies

What are the limitations in creativity and generalization?

Model lacks true creativity and struggles with out-of-domain prompts

How does dataset size impact performance?

Smaller datasets lead to higher loss and repetitive outputs

These experiments highlight why modern language models rely on large datasets and attention-based architectures.

# 📊 Visualization

Training loss curve plotted across epochs

Shows rapid early learning followed by gradual convergence

Demonstrates diminishing returns typical of small datasets

# 🧠 Key Learnings

Gained hands-on experience building an LSTM from scratch

Understood how sequence length affects contextual learning

Learned why LSTMs struggle with long-range dependencies

Connected classical RNN-based LMs to modern transformer-based models

Practiced structured experimentation and analysis in NLP

# 🚀 How to Run

Open the notebook in Google Colab or Jupyter Notebook

Run cells sequentially from top to bottom

Experiment with:

Sequence length

Temperature values

Custom text prompts

# 🔮 Future Improvements

Train on a larger and more diverse dataset

Move from character-level to word-level modeling

Introduce attention mechanisms

Compare performance with Transformer-based models


