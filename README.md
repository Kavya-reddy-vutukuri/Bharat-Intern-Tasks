# Bharat-Intern-Data Science Internship-Tasks

# Task 1 - Stock Prediction

### AIM : TO PREDICT THE STOCK PRICE OF A COMPANY USING LSTM.

### DATASET INFORMATION:


### GOOGLE STOCK PREDICTION

This dataset comprises historical data related to Google's stock prices and various associated attributes. It contains 14 columns and a smaller subset of 1257 rows. Each column represents a specific attribute, and each row contains the corresponding values for that attribute.

The columns in the dataset are as follows:

 1. Company Symbol: Represents the name of the company, which, in this case, is GOOG for Google.
 2. Date: Indicates the year and date of the stock data.
 3. Close: Denotes the closing price of Google's stock on a particular day.
 4. High: Represents the highest value reached by Google's stock on the given day. 
 5. Low: Represents the lowest value reached by Google's stock on the given day.
 6. Open: Indicates the opening value of Google's stock on the given day.
 7. Volume: Represents the trading volume of Google's stock on the given day, i.e., the number of shares traded.
 8. Adjusted Close: Denotes the adjusted closing price of Google's stock, considering factors such as dividends and stock splits.
 9. Adjusted High: Represents the adjusted highest value reached by Google's stock on the given day.
10. Adjusted Low: Represents the adjusted lowest value reached by Google's stock on the given day.
11. Adjusted Open: Indicates the adjusted opening value of Google's stock on the given day
12. Adjusted Volume: Represents the adjusted trading volume of Google's stock on the given day, accounting for factors such as stock splits.
13. Dividend Cash Amount: Denotes the amount of cash dividend paid out to shareholders on the given day.
14. Split Factor: Represents the split factor, if any, applied to Google's stock on the given day. A split factor of 1 indicates no split.

You can find the dataset available on Kaggle at the following link: https://www.kaggle.com/datasets/shreenidhihipparagi/google-stock-prediction


### WORKFLOW OVERVIEW:
### This project involves the following steps:

 1. Importing libraries and the dataset to be used for analysis.
 2. Gathering insights from the dataset to understand its structure and contents.
 3. Performing data pre-processing to prepare the data for model training.
 4. Creating an LSTM (Long Short-Term Memory) model for stock price prediction.
 5. Visualizing the actual stock prices vs. the predicted stock prices using the LSTM model.
 6. Utilizing the trained model to predict stock prices for the upcoming 15 days.



# Task 2 - Titanic Classification

### AIM:
The sinking of the Titanic on April 15, 1912, during its maiden voyage, is a tragic and well-known historical event. The collision with an iceberg resulted in the loss of 1502 out of 2224 passengers and crew members. The disaster had a profound impact on global safety regulations for ships.

While chance played a role in survival, it has been observed that certain groups of people were more likely to survive than others.

As part of this challenge, the goal is to develop a predictive model that can answer the question: "What characteristics made people more likely to survive?" The dataset provided contains passenger data, including attributes like name, age, gender, and socio-economic class.

You are tasked with utilizing this dataset from Kaggle to create a predictive model that can identify the factors associated with survival during the Titanic tragedy. The project presents an opportunity to gain insights into historical events and apply data analysis and machine learning techniques to understand the determinants of survival on the Titanic.

It is important to approach this challenge with sensitivity and respect for the victims and their families, given the historical significance of the event.



## STEPS INVOLVED IN THE PROJECT:

### 1. Problem Understanding and Definition:
   - Understand the objective of the project: Building a predictive model to determine factors influencing survival on the Titanic.
   - Define the problem: Predicting the likelihood of passenger survival based on various attributes.

### 2. Data Loading and Importing the Necessary Libraries:
   - Load the Titanic dataset from the provided source.
   - Import essential Python libraries for data analysis and machine learning.

### 3. Data Understanding using Exploratory Data Analysis (EDA):
   - Perform exploratory data analysis to gain insights into the dataset.
   - Visualize data using plots and charts to identify patterns, correlations, and missing values.
   - Explore survival rates based on different passenger attributes (e.g., gender, age, socio-economic class).

### 4. Feature Engineering and Data Processing:
   - Handle missing values by imputation or removal.
   - Convert categorical variables into numerical representations (encoding).
   - Create new features that might enhance the model's predictive power.

### 5. Model Selection, Training, and Evaluation:
   - Choose appropriate machine learning algorithms for classification (e.g., logistic regression, decision trees, random forests, SVM).
   - Split the data into training and testing sets.
   - Train the selected model on the training data.
   - Evaluate the model's performance using metrics like accuracy, precision, recall, F1-score, and AUC-ROC.

### 6. Model Evaluation and Fine-tuning:
   - Assess the model's performance and adjust hyperparameters if needed for better results.
   - Validate the model using cross-validation techniques to ensure its generalizability.
   - Interpret the model's feature importance to identify the significant factors influencing survival.

### 7. Conclusion and Reporting:
   - Summarize the findings and conclusions from the analysis.
   - Report the final model's performance and its ability to predict survival on the Titanic.
   - Provide actionable insights and recommendations based on the results.



