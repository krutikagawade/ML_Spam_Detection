# Machine Learning Model Implementation – Spam Email Detection


## Project Description

This project implements a **Spam Email Detection system** using Machine Learning.
The model classifies messages into **Spam** or **Not Spam (Ham)** using the **Scikit-learn library**.

The dataset used in this project contains SMS messages labeled as spam or ham.
Text data is converted into numerical form using **CountVectorizer**, and a **Multinomial Naive Bayes classifier** is used to train the model.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Dataset

The dataset used is the **SMS Spam Collection Dataset**.

Each message is labeled as:

* **Ham** – Normal message
* **Spam** – Unwanted promotional or fraudulent message

Example:

| Label | Message                               |
| ----- | ------------------------------------- |
| ham   | Hello, how are you?                   |
| spam  | Congratulations! You won a free prize |

---

## Machine Learning Process

The following steps were performed in the project:

1. Import required libraries
2. Load the dataset
3. Data preprocessing and cleaning
4. Convert text data into numerical features using CountVectorizer
5. Split dataset into training and testing sets
6. Train a Multinomial Naive Bayes classifier
7. Predict results on test data
8. Evaluate model performance using accuracy and confusion matrix

---

## Model Evaluation

The model is evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

These metrics help determine how well the model distinguishes between spam and non-spam messages.

---

## Project Structure

```
Spam-Detection-ML
│
├── spam_detection.ipynb
├── spam.csv
├── README.md
```

---

## Requirements

Install required libraries using:

```
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## How to Run the Project

1. Download the dataset (spam.csv)
2. Open the **Jupyter Notebook**
3. Run all the cells in order
4. The model will train and display evaluation results

---

## Conclusion

This project demonstrates how **Machine Learning can be used to classify spam messages**.
Using Scikit-learn and text processing techniques, the model can accurately predict whether a message is spam or not.

---

