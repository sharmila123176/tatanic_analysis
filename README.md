## Titanic Dataset Analysis - Project Description
Objective:
To analyze passenger data from the Titanic voyage and build a machine learning model to predict whether a passenger survived or not.

## Dataset Overview:
The Titanic dataset is a classic classification dataset provided by Kaggle. It contains information about passengers on the Titanic such as:
PassengerId: Unique ID for each passenger
Survived: Target variable (0 = No, 1 = Yes)
Pclass: Ticket class (1st, 2nd, 3rd)
Name, Sex, Age: Personal information
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Ticket, Fare: Ticket number and fare
Cabin, Embarked: Cabin number and port of embarkation

## Analysis Steps:
Data Cleaning & Preprocessing:
Handled missing values (e.g., imputed missing Age and Embarked).
Converted categorical variables (like Sex, Embarked) into numeric using label encoding or one-hot encoding.
## Exploratory Data Analysis (EDA):
Visualized survival rates by gender, age group, and class.
Identified that:
Women had a higher survival rate.
First-class passengers were more likely to survive.
Children had better survival chances than adults.
## Feature Engineering:
Created new features like FamilySize = SibSp + Parch + 1.
Categorized Age into bins.
Model Building:
Split data into training and validation sets using train_test_split.
Applied machine learning algorithms like:
Logistic Regression
Random Forest
Decision Tree
Tuned hyperparameters to improve accuracy.
Model Evaluation:
Used accuracy, confusion matrix, precision, and recall to evaluate performance.
Logistic Regression achieved reasonable accuracy due to the linear separability of features like Sex and Pclass.
## Technologies Used:
Python
Pandas – Data manipulation
Matplotlib / Seaborn – Visualization
Scikit-learn – Model building and evaluation
## Conclusion:
The Titanic project demonstrates how data science can be used to extract meaningful patterns from real-world data. It emphasizes the importance of data preprocessing, feature selection, and model evaluation in building a reliable predictive model.

