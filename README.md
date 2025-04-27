# Sentiment-Analysis-on-Customer-Reviews

This project focuses on performing Sentiment Analysis on customer reviews using Machine Learning techniques.  
It aims to classify reviews as **Positive** or **Negative** based on the text content.

## Project Overview

- **Problem Type:** Supervised Machine Learning (Classification)
- **Data:** A labeled dataset containing customer reviews and their corresponding sentiments.
- **Goal:** Build a predictive model that can accurately classify new customer reviews.

## Key Steps

1. **Data Preprocessing**
   - Removal of punctuations and stopwords
   - Lowercasing text
   - Tokenization and cleaning

2. **Feature Extraction**
   - Using **TF-IDF Vectorizer** to convert text into numerical features.

3. **Model Building**
   - Logistic Regression classifier was trained on the transformed data.

4. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
   - Classification report (Precision, Recall, F1-Score)

## Technologies Used

- Python
- Pandas
- Numpy
- Scikit-learn
- NLTK (for text preprocessing)
- Jupyter Notebook
