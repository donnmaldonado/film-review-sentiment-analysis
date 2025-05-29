# 🎬 Film Review Sentiment Analysis

## 📝 Overview

This project applies **sentiment analysis** to IMDb film reviews using Natural Language Processing (NLP) and machine learning techniques. The goal is to classify reviews as **positive** or **negative**, helping stakeholders in the entertainment industry better understand viewer sentiment and inform data-driven decisions.

## 🔍 Objective

To compare the performance of various classification algorithms in identifying the sentiment of movie reviews, using vectorized text representations from Word2Vec.

## 📊 Workflow

1. **Data Source**
   - IMDb movie reviews dataset (CSV format) from Kaggle.

2. **Exploratory Data Analysis (EDA)**
   - Performed to identify data quality issues and distribution patterns.

3. **Data Cleaning**
   - Converted text to lowercase
   - Removed HTML tags, URLs, punctuation, emojis, digits, and stop words

4. **Text Vectorization**
   - Applied **Word2Vec** (Skip-gram) to convert textual reviews into 500-dimensional numeric vectors.

5. **Model Training**
   - Trained and tuned multiple classification models:
     - Logistic Regression
     - Support Vector Machine (SVM)
     - Random Forest
     - Decision Tree
     - XGBoost
     - Multi-Layer Perceptron (MLP)

6. **Hyperparameter Tuning**
   - Used `GridSearchCV` for optimal model configurations.
   - Explored varying Word2Vec vector lengths to optimize performance.

## 🏆 Best Model

- ✅ **Multi-Layer Perceptron (MLP)**
  - Architecture: Two hidden layers (sizes 100 and 200)
  - Performance: **F1-score = 0.8911**
  - Vectorization: Word2Vec with embedding size of 500

Data
---
<img width="336" alt="Image" src="https://github.com/user-attachments/assets/e393f947-9ec9-4086-90b0-4caf4d4cf420" />

EDA
---
![image](https://github.com/user-attachments/assets/8259caaf-c55a-4f92-8bff-ce37321bb9c8)


<img width="855" alt="Screenshot 2025-01-23 at 5 51 04 PM" src="https://github.com/user-attachments/assets/834f9851-4f0d-422f-9df8-9441de1d3d6c" />

Results
---
![Image](https://github.com/user-attachments/assets/050bfa35-1388-47ec-a3fb-58586fa98358)

![Image](https://github.com/user-attachments/assets/2eb77260-e036-4231-8ca5-3ac8a843d547)





Links
---
[Data Source](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data)

