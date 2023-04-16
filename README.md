Diabetes Dataset: Model Development and Comparison

This repository contains code for developing and comparing different machine learning models on the diabetes dataset. The diabetes dataset contains information about 768 women of Pima Indian heritage who were at least 21 years old and living near Phoenix, Arizona, and the aim of the project is to predict whether a given patient will develop diabetes within 5 years based on various features such as age, BMI, blood pressure, and others.


Dataset

The diabetes dataset can be found in the data folder of this repository. The dataset consists of a CSV file named diabetes.csv. This file contains 768 rows and 9 columns, where each row represents a patient and each column represents a feature. The column names are:

•	pregnancies: number of times pregnant

•	glucose: plasma glucose concentration a 2 hours in an oral glucose tolerance test

•	blood_pressure: diastolic blood pressure (mm Hg)

•	skin_thickness: triceps skin fold thickness (mm)

•	insulin: 2-Hour serum insulin (mu U/ml)

•	bmi: body mass index (weight in kg/(height in m)^2)

•	diabetes_pedigree_function: diabetes pedigree function

•	age: age (years)

•	outcome: Class variable (0 or 1) indicating whether the patient developed diabetes within 5 years.


Requirements

To run the code in this repository, you will need Python 3.7 or higher and the following libraries:

•	NumPy

•	Pandas

•	Scikit-learn


Code

The code for developing and comparing different machine learning models can be found in the Diabetes_prediction.ipynb Jupyter notebook. This notebook contains the following sections:

•	Data loading and exploration

•	Data preprocessing

•	Model development and comparison

In the Model development and comparison section, we develop and compare the following machine learning models.

•	Support Vector Machine (SVM)

•	Random Forest

•	Logistic Regression

•	Decision Tree

•	KNN

I used the accuracy score as an evaluation metric.

Usage

To use this repository, simply clone or download the repository to your local machine and run the Diabetes_prediction.ipynb Jupyter notebook. You can modify the code in the notebook to try out different models or evaluation metrics.

Contributing

If you have any suggestions for improving this repository or adding new models, feel free to submit a pull request or open an issue. We welcome contributions from the community!

