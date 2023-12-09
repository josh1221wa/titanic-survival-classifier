# Titanic Survival Classifier

This script performs analysis and prediction on the Titanic dataset. It includes data visualization, preprocessing, and the training of a Decision Tree classifier for predicting survival.

## Dataset Overview

The dataset is loaded from a CSV file, and initial exploratory data analysis is conducted. Columns such as 'Name', 'Ticket', and 'Cabin' are dropped due to their limited contribution. Missing values are handled, duplicates are removed, and various visualizations are created.

## Data Visualization

- **Pie Chart:** Displays the distribution of survived and died passengers.
- **Bar Plots:** Show the distribution of categorical features ('Survived', 'Pclass', 'Sex', 'SibSp', 'Parch', 'Embarked').
- **Histograms and Pair Plot:** Visualize the distribution and relationships of numerical features like 'Age', 'Fare', and their correlation with survival.

## Data Preprocessing

- Gender ('Sex') and Embarked Port ('Embarked') are encoded into numeric values.
- Outliers in numerical features are handled using the IQR method.

## Data Resampling

- Synthetic Minority Over-sampling Technique (SMOTE) is used to balance the class distribution.

## Model Training and Evaluation

- The dataset is split into training and testing sets.
- Standardization is applied to numerical features using StandardScaler.
- A Decision Tree classifier is trained on the data.
- Model evaluation metrics (precision, recall, F1-score) and a confusion matrix are displayed.

## Decision Tree Visualization

- The Decision Tree model is visualized using Graphviz.

## Conclusion

This Titanic Survival Prediction project aims to provide insights into the dataset and predict passenger survival using a Decision Tree classifier. Through data visualization, preprocessing, and modeling, we gained valuable information about the factors influencing survival on the Titanic.

The script employs various visualization techniques to understand the distribution of features and their relationships with survival. Data preprocessing ensures the dataset is clean and ready for model training. The Decision Tree classifier is chosen for its interpretability and is trained on the preprocessed data.

The model evaluation metrics and confusion matrix provide a comprehensive view of the model's performance. The Decision Tree visualization aids in understanding the decision-making process of the model.

By following the provided usage instructions, users can easily reproduce the analysis and leverage the insights gained for further investigation or improvement of the predictive model.
