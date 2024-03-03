# Machine Learning in Finance (FS2022) - Final Project
This is the final project of group 2 for the Seminar Introduction to Machine Learning (03SMBOEC0385). Our group used Google Colab to simplify collaboration. To load the data we used !git clone to clone the repository with the data on Google Colab. In case you want to run the jupyter notebook on your own device instead, you can also download the data from this repository and change the filepath in pd.read_csv() to the filepath of the data.

# Table of Contents
1. [Team Members](##team-members)
2. [Project Overview](##project-overview)
3. [Key Features](##key-features)
4. [Models Evaluated](##models-evaluated)
5. [Getting Started](##getting-started)
6. [Results](##results)
7. [Future Work](##future-work)

## Team Members
- Jan Heinrich Schlegel
- Robert Bibaj
- Simon Klaassen
- Thomas Meier


## Project Overview
Our project explores the application of various machine learning models to predict stock performance based on historical financial data from 2014 to 2018. The project entails data preprocessing, feature engineering, model selection, and evaluation to address challenges such as class imbalances, missing values, and outliers. We rigorously tested models including Logistic Regression, Gaussian Naive Bayes, Random Forest, XGBoost, Support Vector Machine, and Feedforward Neural Networks to identify the most effective predictors of stock recommendations.

## Key Features
- Data concatenation and preprocessing to handle missing values and outliers.
- Implementation of KNN imputation and Isolation Forest for data cleaning.
- Feature engineering based on the Sustainable Growth Model and financial ratios.
- Evaluation of model performance using the weighted F1-score as the primary metric.
- Analysis of class imbalances with techniques like RandomOverSampler for balanced training.

## Models Evaluated
- Logistic Regression
- Gaussian Naive Bayes
- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- Feedforward Neural Networks with multiple hidden layers and dropout

## Getting Started
To run the analysis:
1. Ensure you have Jupyter Notebook or JupyterLab installed.
2. Clone the repository and navigate to the project folder.
3. Open `ML_in_Finance_Group2_FinalProject.ipynb` in Jupyter.
4. Install required Python packages listed in the beginning of the jupyter notebook.
5. Execute the notebook cells sequentially to replicate our findings.

## Results
Our findings indicate that while traditional and simple models like logistic regression perform adequately, gradient boosting models like XGBoost, when finely tuned, can outperform more complex algorithms on tabular data. The project underlines the importance of feature engineering and model selection in financial data analysis.

## Future Work
The project opens avenues for further exploration, such as portfolio performance analysis based on model predictions, extension to non-US stocks, and advanced feature engineering to mitigate data leakage and enhance model accuracy.
