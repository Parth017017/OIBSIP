# Email Spam Detection using Machine Learning 

## Oasis Infobyte Data Science Internship 2026

**Intern:** Parth Prajapati

---

## Project Title
Email Spam Detection

## Problem Statement

Email spam refers to unwanted and unsolicited messages sent to users. Spam emails can contain advertisements, scams, phishing attempts, or malicious content.

The goal of this project is to build a Machine Learning model that can automatically classify emails as:

- Spam
- Not Spam (Ham)

---

## Objective

- Analyze email text data.
- Perform text preprocessing.
- Convert text into numerical features.
- Train a machine learning model.
- Predict whether an email is spam or legitimate.

---

## Dataset

The dataset contains:

- Email Message
- Label (Spam or Ham)

Dataset Features:

- Text Content
- Target Variable (Spam/Ham)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- NLP Techniques

---

## Project Workflow

### 1. Import Libraries

Imported required libraries for:

- Data Analysis
- Text Processing
- Machine Learning

### 2. Load Dataset

Loaded the email dataset using Pandas.

### 3. Data Cleaning

Performed:

- Missing value handling
- Duplicate removal
- Data formatting

### 4. Text Preprocessing

Applied:

- Lowercasing
- Tokenization
- Stopword Removal
- Text Cleaning

### 5. Feature Extraction

Converted text into numerical format using:

- Count Vectorizer / TF-IDF Vectorizer

### 6. Model Training

Machine Learning algorithms were used to classify emails into spam and non-spam categories.

### 7. Model Evaluation

Evaluated performance using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Results

Key Outcomes:

- Successfully classified spam and non-spam emails.
- Achieved high prediction accuracy.
- Reduced the risk of unwanted email messages.

---

## Project Structure

```

Task_4_Spam_Email/
│
├── Task_4_Spam_Email.ipynb
├── spam.csv
├── README.md
└── screenshots/

```

---

## How to Run

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```text
Task_4_Spam_Email.ipynb
```

Run all cells.

---

## Learning Outcomes

- Natural Language Processing (NLP)
- Text Preprocessing
- Feature Engineering
- Classification Algorithms
- Model Evaluation
- Machine Learning Workflow

---

## Internship

This project was completed as part of the Oasis Infobyte Data Science Internship Program.
