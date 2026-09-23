# Naive Bayes — SMS Spam Classification

This project implements a machine learning model to classify SMS messages as **Spam** or **Ham (Not Spam)** using the **Multinomial Naive Bayes** algorithm.

## Dataset

The project uses the **SMS Spam Collection** dataset, containing labeled SMS messages classified as either `spam` or `ham`.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* Multinomial Naive Bayes
* CountVectorizer

## Workflow

1. Load and clean the SMS dataset
2. Convert labels into numerical values
3. Split the data into training and testing sets
4. Convert text messages into numerical vectors using CountVectorizer
5. Train a Multinomial Naive Bayes classifier
6. Evaluate the model using:

   * Accuracy
   * Precision
   * Recall
   * F1-score
   * Confusion Matrix
7. Identify words strongly associated with Spam and Ham
8. Test the trained model on new SMS messages

## Files

* `week7_ML_FA26.ipynb` — Complete Jupyter Notebook containing the implementation and results
* `spam.csv` — SMS Spam Collection dataset

## Model

The project uses **Multinomial Naive Bayes**, which is well suited for text classification because it works effectively with word-count features.

## Author

**Adeel Ashfaque**
BS Computer Science
Sukkur IBA University
