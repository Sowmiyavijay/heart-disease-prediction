# Heart Disease Prediction

This is a machine learning project where I’ve built a model to predict whether a person has heart disease based on some basic clinical information.

## About the Dataset

The dataset contains various medical details about patients, like:

- Age, sex
- Type of chest pain
- Blood pressure, cholesterol levels
- Maximum heart rate
- ST depression, ECG results
- Whether they have exercise-induced angina

The target column indicates whether the person has heart disease (1) or not (0).

## What I Did

- Explored the data and understood the columns
- Preprocessed the data (handled categories, scaled values)
- Trained two models: Logistic Regression and Random Forest
- Evaluated the performance using accuracy, precision, recall, ROC curve, and feature importance

## Results

Both models gave good results, but Random Forest performed the best overall.  
Some of the most important features were chest pain type, maximum heart rate, and ST depression (oldpeak).

## Files

- `heart.csv`: the dataset
- `heart_disease.ipynb`: my notebook with all the code, training, and results

## How to Run It

You can open the notebook in Google Colab or Jupyter Notebook, upload the CSV file, and run all the cells to see the output.
