# Medication Selection with Machine Learning Models

## Project Overview

The objective of this project is to develop and compare machine learning models that assist healthcare providers in selecting the most appropriate medication for a patient, based on factors such as blood pressure, cholesterol level, Na/K ratio, age, and sex.

## Dataset

The dataset used in this project is from Kaggle. It contains patient data with features like blood pressure, cholesterol levels, Na/K ratio, age, and sex, which are used to predict the most suitable medication for a patient.

Link to the dataset: [Kaggle Dataset](https://www.kaggle.com/datasets/prathamtripathi/drug-classification)

## Models Implemented

- Logistic Regression
- Decision Tree

The models are evaluated using accuracy, and hyperparameters are tuned for optimal performance.

## Installation

To run the project, you will need Python with the following libraries:

- pandas
- scikit-learn
- matplotlib

## Conclusion

This project demonstrates the application of machine learning models in healthcare for assisting providers in making informed decisions about patient medication selection.

Two machine learning models, Logistic Regression and Decision Trees, were implemented and compared. 

Initially, the Decision Tree model showed an impressive performance of 97.5% accuracy on the training data, but it faced overfitting when tested. 
To address this, I fine-tuned the model by binning one of the variables, which resulted in a more realistic accuracy of 87.5%. The model also exhibited consistent results with good train and test accuracy, as well as solid cross-validation performance.

Logistic Regression also performed well, achieving an accuracy of 85%. 

Both models showed promising results. However, there is still room for improvement in refining the models, such as testing with a larger dataset and exploring other algorithms.

The dataset used in this project was also very simplified and quite small, but this was my first time building models and my main purpose was to explore and understand how machine learning models work and how fine-tuning the parameters influence their performance.

In summary, this project demonstrates that machine learning can offer valuable insights in healthcare decision-making, but it requires continuous evaluation and optimization to ensure its practical application in real-world scenarios.


  
