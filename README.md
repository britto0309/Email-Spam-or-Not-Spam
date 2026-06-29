# Email Spam Detection using Logistic Regression

## About the Project

Email spam detection is a common text classification problem in machine learning. This project builds a simple spam classifier using **Logistic Regression** and **TF-IDF Vectorization** to determine whether an email is **Spam** or **Not Spam** based on its content.

The model is trained on a sample dataset containing both spam and non-spam emails. Users can enter a custom email message, and the application predicts the probability of it being spam.

---

## Technologies

* Python
* Pandas
* Matplotlib
* Scikit-learn

---

## Machine Learning Techniques

This project applies the following techniques:

* Text preprocessing using **TF-IDF Vectorizer**
* Logistic Regression for binary classification
* Probability-based prediction using `predict_proba()`
* Model evaluation with a Confusion Matrix

---

## Dataset

The dataset consists of two categories:

* Spam emails containing promotional offers, rewards, prizes, and advertisements.
* Non-spam emails containing regular messages such as meetings, assignments, reports, and project updates.

Each email is labeled as either:

* **1** – Spam
* **0** – Not Spam

---

## Workflow

The implementation follows these steps:

1. Create a labeled email dataset.
2. Convert email text into numerical features using TF-IDF.
3. Train a Logistic Regression classifier.
4. Evaluate the model using training accuracy.
5. Accept an email message from the user.
6. Predict the probability of the email being spam.
7. Display the final classification and confusion matrix.

---

## Sample Prediction

The application accepts an email message as input and returns:

* Spam Probability
* Predicted Category (Spam or Not Spam)

---

## Future Enhancements

* Train the model using a larger real-world email dataset.
* Apply text preprocessing techniques such as stop-word removal and stemming.
* Compare Logistic Regression with Naive Bayes and Support Vector Machine classifiers.
* Deploy the model as a web application using Streamlit or Flask.
* Improve model performance through cross-validation and hyperparameter tuning.

---

## Author

**Britto Domnic Aro J**

Aspiring Machine Learning Engineer | Python Developer | Data Analytics Enthusiast
