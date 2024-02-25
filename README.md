# Cloth Manufacturing Company Sales Analysis

# Overview of Project
- This project aims to analyze the sales data of a cloth manufacturing company to identify the factors that contribute to high sales. 
- The dataset consists of various attributes such as unit sales, competitor price, community income level, advertising budget, population size, etc.

# Problem Statement
- The cloth manufacturing company wants to understand which segments or attributes lead to high sales. To address this, we will build a Random Forest model with the target variable as sales (converted into a categorical variable) and all other variables as independent features.

# Approach
## Data Preprocessing
- Handle missing values.
- Convert categorical variables into dummy variables.
- Convert the target variable Sales into a categorical variable.

## Exploratory Data Analysis (EDA)  
- Analyze the distribution of each variable.
- Explore relationships between variables using visualizations like scatter plots, histograms, box plots, etc.
- Identify any outliers or anomalies.

## Model Training and Validation
- Split the data into training and testing sets.
- Train a Random Forest model on the training data.
- Validate the model using the testing data.
- Evaluate the model's performance using appropriate metrics such as accuracy, precision, recall, and F1-score.

## Inference  
- Interpret the results of the trained model.
- Identify which attributes have the most influence on Sales.
- Provide actionable insights for the cloth manufacturing company based on the model's findings.

# Conclusion

## Key Factors Influencing Sales
- The Random Forest model revealed that variables such as competitor price, advertising budget, and income level significantly impact sales.

## Shelf Location Importance
-  Shelf location at stores also plays a role in sales, with products placed in "Good" quality locations showing higher sales compared to "Bad" or "Medium" quality locations.

## Urban vs. Rural Impact
- The analysis indicates that stores located in urban areas tend to have higher sales compared to rural areas.

# Results
- The script will perform data preprocessing, exploratory data analysis, model training, and inference generation.
- Classification reports and feature importance scores will be printed to the console.
