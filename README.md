# 📩 SMS Spam Detection

This project is a Machine Learning based SMS Spam Detection system that classifies messages as **Spam** or **Ham (Not Spam)**.

## 🚀 Project Workflow

1. Data Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Text Preprocessing  
4. Feature Extraction using TF-IDF  
5. Model Training & Evaluation  
6. Model Selection  
7. Web App & Deployment  

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

## 🔍 Text Preprocessing Steps

- Convert text to lowercase
- Tokenization
- Remove punctuation & special characters
- Remove stopwords
- Stemming

## 🤖 Machine Learning Algorithms Used

The following algorithms were trained and evaluated:

- Multinomial Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Random Forest
- Decision Tree
- Extra Trees Classifier
- XGBoost

## ✅ Selected Model

After comparing different models based on **Accuracy** and **Precision Score**,  
**Multinomial Naive Bayes** was selected as the final model because it performed best for SMS text classification.

## 📊 Feature Extraction

TF-IDF Vectorizer is used to convert text messages into numerical format for machine learning models.

## 📌 Project Goal

To build a simple and efficient system that can automatically detect spam SMS messages.

## ▶️ Run the Project

```bash
pip install -r requirements.txt
```

Run the notebook or application file to test the model.

---

⭐ If you like this project, feel free to star the repository.
