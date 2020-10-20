# House-Price-Prediction

## Table of Contents

Process of Machine Learning Predictions
Housing Data Set
1) Understand the problem
2) Generate Hypothesis 
3) Get Data
4) Exploratory Data Analysis (EDA)
5) Data Pre-Processing
6) Feature Engineering 
7) Model Training 
8) Model Evaluation
9) Model Testing

Process of Machine Learning: 

"Keep tormenting the data until it starts revealing its hidden secrets". Well, it can be done, but, there's a way around. Machine learning projects are not about grabbing data and feeding it to a algorithm and make predictions. A good machine learning project involve the below steps.

1) Understand the problem:_ One of the most import and critical step in any data related project is to understand the problem we are trying to solve. Understanding the domain plays a very importand role. 

2) Generate Hypothesis: This is very important step but most often forgotten. Hypothesis generation is an educated “guess” of various factors that could impact the business problem that needs to be solved using machine learning. It hepls in understanding what data to be collected that and from where, key in converting your business problem into a data science problem. This should be done before looking at the data to avoid bias. If done adequately, you would have included all the variables available in the dataset and might include variables that are not present in the dataset.

3) Get Data: Now that we know what features to get, we looks at various sources to obtain the data. Determine which features are available, which are not. Compare the list of features generated in hypothesis generation to determine which hit the mark, and which ones could be created. This step often helps in creating new features.

4) Exploratory Data Analysis (EDA): In this step, we dig deep into the data, summarize their main characteristics and visuvalize. EDA is done to understand what the data can tell us beyond the formal modeling or hypothesis testing task. EDA helps you confirming and validating the hypothesis you make.

5) Data Preprocessing: In this step, data cleaning and imputing missing values in done. This step is usually followed along with EDA.

6) Feature Engineering: In this step, new features are created and added to the dataset. Most of the ideas for creating new features come form hypothesis generation stage. 

7) Model Training: A suitable alogorith is used to train the model on the dataset.

8) Model Evaluation: The trained model's performance is evaluated using a suitable error metric. In this step, variable importance is evaluated, i.e,, which variables have proved to be significant in determining the target variable. The best variables are shortlisted and the model is trained and evaluated again. 

9) Model Testing: Finally the model is tested on unseen dataset.

The above steps are followed in this project to arrive at final prediction.

1. Understand the Problem: The dataset for this project has been taken from Kaggle's Housing Data  Knowledge Competition https://www.kaggle.com/c/house-prices-advanced-regression-techniques. The aim of this project is to predict the house prices in Ames, Iowa using the 79 explanatory variables which describe (almost) every aspect of residential homes.
