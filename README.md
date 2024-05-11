# IBM HR Analytics Attrition Dataset Analysis
This repository contains Python code for analyzing the IBM HR Analytics Attrition Dataset using machine learning models such as Logistic Regression, Random Forest, and Support Vector Machine (SVM). The code preprocesses the dataset, trains multiple models, performs hyperparameter tuning using GridSearchCV, and evaluates the models' performance.

## Requirements
Python 3.x
pandas
numpy
scikit-learn
matplotlib (optional for visualization)
Dataset
The dataset used in this analysis is the IBM HR Analytics Attrition Dataset, which can be found on kaggle. Please download the dataset and place it in the same directory as the Jupyter Notebook file.

## Instructions
Clone this repository or download the Jupyter Notebook file (IBM_HR_Analytics_Attrition.ipynb).
Download the dataset from kaggle.
Install the required Python libraries listed in the Requirements section using pip:
```bash
pip install pandas numpy scikit-learn matplotlib
```
Open the Jupyter Notebook file in Jupyter Notebook or Jupyter Lab.
Run the cells in the notebook sequentially to preprocess the data, train the models, perform hyperparameter tuning, and evaluate the models' performance.
The notebook will print classification reports for each model, showing precision, recall, F1-score, and accuracy.
Additionally, the notebook will display the best parameters for each model after hyperparameter tuning.

## Additional Information
The dataset contains various features related to employees' demographics, job roles, and performance ratings, along with the target variable 'Attrition', indicating whether an employee has left the company.
The code preprocesses the data by encoding categorical variables and scaling numerical features.
Three different classifiers are trained: Logistic Regression, Random Forest, and Support Vector Machine (SVM).
Hyperparameter tuning is performed using GridSearchCV to optimize each model's performance.
Evaluation metrics such as precision, recall, F1-score, and accuracy are used to assess the models' performance.
Feel free to customize this README file according to your preferences or add any additional information you think might be helpful!
