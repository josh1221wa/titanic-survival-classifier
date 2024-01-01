# Titanic Survival Classifier

## Introduction

The RMS Titanic was a British passenger liner that sank in the North Atlantic Ocean on the night of April 14-15, 1912, after striking an iceberg during her maiden voyage from Southampton to New York City. At the time of her construction, she was the largest ship afloat and was considered the most luxurious passenger ship ever built.

The disaster was caused by a combination of factors, including the ship's speed, the lack of lifeboats, and the failure of the crew to properly manage the evacuation. The sinking of the Titanic was one of the deadliest commercial peacetime maritime disasters in modern history. It led to major changes in maritime safety regulations, including the requirement for ships to carry enough lifeboats for all passengers and crew.

In this notebook we will analyze a dataset containing information about the passengers aboard the Titanic and predict whether a passenger survived or not based on the available features.

## Dataset Used

The dataset used in this particular analysis is from Kaggle. It contains information about the passengers aboard the Titanic. The dataset can be downloaded from [here](https://www.kaggle.com/datasets/yasserh/titanic-dataset).

## Modules Used

- `pandas` for data manipulation
- `matplotlib` and `seaborn` for data visualization
- `scikit-learn` for data preprocessing, model training, and evaluation
- `graphviz` and `pydotplus` for Decision Tree visualization

## Installation

To run the code in this repository, you need to install the required dependencies. You can do this by following these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Open a terminal or command prompt.
4. Run the following command to install the dependencies using pip:

    ```shell
    pip install -r requirements.txt
    ```

This command will install all the necessary packages listed in the `requirements.txt` file.

## Steps Followed

### 1. Data Cleaning

In this step, the unnecessary columns are dropped and the missing and duplicate values are handled.

### 2. Exploratory Data Analysis

In this step, the distribution of features is visualized and their relationships with survival are analyzed.

### 3. Data Preprocessing

In this step, the categorical features are encoded, the outliers are dropped and the dataset is split into training and test sets. The numerical data is also scaled using StandardScaler.


### 4. Model Training and Testing

In this step, the Decision Tree classifier is trained on the preprocessed data. The model is then evaluated using various metrics and the confusion matrix.

### 5. Decision Tree Visualization
    
In this step, the Decision Tree classifier is visualized using the graphviz library.

## Results

The Decision Tree classifier achieved an accuracy of 0.81 on the test set. The confusion matrix shows that the model correctly predicted 142 out of 179 non-survivors and 72 out of 89 survivors. The model achieved a precision of 0.83 and a recall of 0.81.

## Conclusion

This Titanic Survival Prediction project aims to provide insights into the dataset and predict passenger survival using a Decision Tree classifier. Through data visualization, preprocessing, and modeling, we gained valuable information about the factors influencing survival on the Titanic.

The script employs various visualization techniques to understand the distribution of features and their relationships with survival. Data preprocessing ensures the dataset is clean and ready for model training. The Decision Tree classifier is chosen for its interpretability and is trained on the preprocessed data.

The model evaluation metrics and confusion matrix provide a comprehensive view of the model's performance. The Decision Tree visualization aids in understanding the decision-making process of the model.

For more details, please refer to the code comments and the generated README file. Happy coding ❤️
