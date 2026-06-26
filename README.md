# Email-Spam-or-Not-Spam

# 📧 Email Spam Detection using Logistic Regression

## 📌 Project Overview

This project implements an **Email Spam Detection System** using the **Logistic Regression** algorithm from **Scikit-learn**.

The model is trained on a dataset containing spam and non-spam email messages. It converts the email text into numerical features using **TF-IDF Vectorization** and predicts whether a new email is **Spam** or **Not Spam**.

The project also evaluates the model's performance using a **Confusion Matrix**.

---

# 🎯 Objectives

* Build an Email Spam Detection model.
* Convert text data into numerical features using TF-IDF.
* Train a Logistic Regression classifier.
* Predict whether a new email is Spam or Not Spam.
* Display the spam probability of the input email.
* Visualize the model performance using a Confusion Matrix.

---

# 🧠 Machine Learning Algorithm

**Algorithm Used:** Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for **classification problems**. It predicts the probability that an email belongs to one of two classes:

* Spam
* Not Spam

---

# 📂 Dataset

The project uses a sample dataset containing **30 email messages**.

### Classes

* **Spam Emails:** 15
* **Not Spam Emails:** 15

### Examples of Spam Emails

* Win a free iPhone now
* Claim your cash prize
* Earn money from home
* Free vacation package

### Examples of Not Spam Emails

* Meeting at 10 AM
* Project review tomorrow
* Please send the report
* Assignment submission reminder

---

# ⚙️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

# 📚 Libraries Used

```python
pandas
matplotlib
scikit-learn
```

---

# 🔄 Project Workflow

1. Create the email dataset.
2. Convert email text into numerical features using **TF-IDF Vectorizer**.
3. Train the Logistic Regression model.
4. Accept a new email from the user.
5. Predict whether the email is Spam or Not Spam.
6. Display the spam probability.
7. Generate the Confusion Matrix.

---

# 📊 Text Vectorization

The project uses **TF-IDF (Term Frequency–Inverse Document Frequency)** to convert email text into numerical values that can be understood by the machine learning model.

This helps the model identify important words that distinguish spam emails from genuine emails.

---

# 📈 Model Evaluation

The model is evaluated using:

### Training Accuracy

Shows how accurately the model predicts the training dataset.

### Confusion Matrix

The Confusion Matrix compares:

* Actual Spam emails
* Actual Not Spam emails
* Predicted Spam emails
* Predicted Not Spam emails

This helps evaluate the classifier's performance.

---

# 🚀 Features

* Email Spam Detection
* Logistic Regression Classifier
* TF-IDF Text Vectorization
* Spam Probability Prediction
* Training Accuracy Display
* Confusion Matrix Visualization
* Interactive User Input

---

# ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/Email-Spam-Detection-Logistic-Regression.git
```

### Navigate to the project folder

```bash
cd Email-Spam-Detection-Logistic-Regression
```

### Install required libraries

```bash
pip install -r requirements.txt
```

### Run the project

```bash
python spam_detection.py
```

---

# 💻 Sample Input

```
Enter Email Text:

Congratulations! You have won a free iPhone. Claim your reward now.
```

---

# 📤 Sample Output

```
Training Accuracy: 100.00%

Spam Probability: 0.96

Result: SPAM EMAIL
```

---

### Another Example

#### Input

```
Meeting scheduled tomorrow at 10 AM.
```

#### Output

```
Spam Probability: 0.08

Result: NOT SPAM EMAIL
```

---

# 📸 Output

The program generates:

* Training Accuracy
* Spam Probability
* Spam/Not Spam Prediction
* Confusion Matrix Visualization

You can also add a screenshot of the confusion matrix in your repository.

```markdown
![Confusion Matrix](confusion_matrix.png)
```

---

# 📁 Project Structure

```
Email-Spam-Detection-Logistic-Regression
│
├── spam_detection.py
├── README.md
├── requirements.txt
├── confusion_matrix.png
└── .gitignore
```

---

# 📖 Learning Outcomes

Through this project, you will learn:

* Text preprocessing
* TF-IDF Vectorization
* Logistic Regression for classification
* Binary Classification
* Probability Prediction
* Model Evaluation
* Confusion Matrix Interpretation

---

# 🔮 Future Improvements

* Train the model using a larger real-world email dataset.
* Add email preprocessing (remove punctuation, stop words, etc.).
* Save and load the trained model using Pickle or Joblib.
* Build a web interface using Streamlit or Flask.
* Improve accuracy using additional machine learning models.

---

# 👨‍💻 Author

**Britto Domnic Aro J**

Machine Learning Enthusiast | Python Developer | AI Learner

---

# ⭐ If you found this project useful, don't forget to Star this repository!
