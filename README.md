# KCB-Data-Science-Hackathon
# Telco Customer Churn Prediction Project

## Overview
This project aims to predict customer churn in a telecommunications company using machine learning techniques. 
The dataset used for analysis is the Telco Customer Churn dataset obtained from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

## Activities
### Importing Libraries
The following libraries were imported for data analysis and modeling:
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Matplotlib: For data visualization.
- Seaborn: For statistical data visualization.
- Scikit-learn: For machine learning modeling and evaluation.

### Exploratory Data Analysis (EDA)
Performed exploratory data analysis to understand the dataset and gain insights. Activities included:

Loading the dataset.
Understanding the structure of the data.
Checking for missing values. There were no missing values
Exploring summary statistics.
Visualizing distributions and relationships in the data.

### Data Preprocessing
Prepare features and target variable for modeling. Dropped two columns during feature selection.

### Visualization
Performed data visualization to gain insights into the dataset. Visualizations included histograms and count plots.

### Model Building and Evaluation
Built machine learning model to predict customer churn. Activities included:

Splitting the data into training and testing sets.
Training the model using K-Nearest Neighbors (KNN).
Evaluating model performance using accuracy metric.

Visualized model Complexity to get a good value of n_neighbors to avoid either overfitting or underfitting.

### Challenges Encountered
Encountered an error with the .map() method while converting churn into binary, resulting in all values being 'NaN'. Resolved by using the .replace() method instead.

Faced a ValueError when using the .fit() method due to categorical variables needing encoding. Solved by encoding categorical variables before fitting the model.

Encountered other minor errors such as spelling mistakes, which were quickly rectified.


#### Conclusion
The performance of the model can be optimized model further by performing hyperparameter tuning. 
