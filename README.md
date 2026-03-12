## 📌 Project Overview

Spam messages are unwanted or harmful messages sent to many users at the same time. These messages often contain advertisements, scams, or phishing links. Detecting spam messages automatically helps protect users from fraud and improves communication safety.

In this project, we build a **Spam Detection System using Python and Machine Learning**. The model learns from a dataset of SMS messages and classifies new messages as **Spam** or **Ham (Not Spam)**.

---

## 🎯 Objectives

* Analyze the SMS Spam dataset.
* Perform data preprocessing and cleaning.
* Visualize the dataset using charts.
* Train machine learning models to detect spam messages.
* Evaluate model performance.

---

## 📂 Dataset

The dataset used in this project is the **SMS Spam Collection Dataset** downloaded from Kaggle.

### Dataset Features

| Column  | Description                |
| ------- | -------------------------- |
| label   | Message type (spam or ham) |
| message | Text content of the SMS    |

Example:

| label | message                             |
| ----- | ----------------------------------- |
| ham   | Go until jurong point, crazy..      |
| spam  | Free entry in a weekly competition! |

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* WordCloud

---

## 📊 Data Visualization

The following visualizations were created to understand the dataset:

* Spam vs Ham count plot
* Pie chart distribution
* Message length histogram
* Word count distribution
* Boxplot comparison
* Scatter plot analysis
* Top spam words bar chart
* Word cloud visualization

These charts help analyze patterns in spam messages.

---

## ⚙️ Machine Learning Models

The following machine learning techniques were used:

* Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)

These models are trained using **TF-IDF text vectorization**.

---

## 🔍 Steps in the Project

1. Import required libraries
2. Load the dataset
3. Data cleaning and preprocessing
4. Feature extraction using TF-IDF
5. Train-test split
6. Train machine learning model
7. Evaluate model accuracy
8. Predict new messages

---

## 📈 Sample Output

Example prediction:

Input Message:

```
Congratulations! You have won a free prize.
```

Output:

```
Spam
```

---

## 📁 Project Structure

```
SMS-Spam-Detection/
│
├── dataset/
│   └── SMSSpamCollection.csv
│
├── programs/
│   ├── data_analysis.py
│   ├── visualization.py
│   ├── spam_classifier.py
│
├── charts/
│   └── visualization_outputs
│
└── README.md
```

---

3. Run the Python programs using VS Code.

```
python spam_detector.py
```

---
