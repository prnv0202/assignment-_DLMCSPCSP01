# Heart Disease Prediction Using Logistic Regression
This project is part of the MSc Computer Science portfolio and mainly focus on solving a real-world healthcare problem: predicting the likelihood of heart disease using clinical data and machine learning.

The goal is to build a logistic regression model that can classify patients as likely or unlikely to have heart disease, based on features like age, cholesterol levels, and resting blood pressure.

 # Files in This Repository
main.ipynb — Jupyter Notebook containing the full code (data loading, model training, evaluation).

HeartDiseaseTrain-Test.csv — The dataset used for training and testing.

## Requirements

 need the following libraries:

pip install pandas numpy scikit-learn matplotlib seaborn

Jupyter Notebook is also required to run the .ipynb file. You can install it via:

pip install notebook

# How to Run

Clone this repository or download the ZIP.

Open a terminal in the project folder.

Run Jupyter Notebook:
jupyter notebook

Open main.ipynb in the browser and run all cells step-by-step.


The notebook begins by loading and previewing the heart disease dataset to understand the structure and features. It then preprocesses the data, including tasks such as scaling the numerical features to ensure uniformity. After preprocessing, a logistic regression model is trained using the scikit-learn library to classify the presence or absence of heart disease. The model’s performance is evaluated using common classification metrics such as accuracy, precision, recall, and a confusion matrix. Finally, the results are visualized using Seaborn and Matplotlib to provide clear insights into model performance and feature relationships.

 # Dataset
The dataset is sourced from Kaggle’s Heart Disease UCI Dataset:
 (https://www.kaggle.com/datasets/mohamedkhairyelbanna/heartdiseasetrain-test)
