# Film Review Sentiment Analysis

Summary
---

Sentiment analysis, leveraging natural language processing to uncover emotions in text, is a
powerful tool for understanding public opinion. This research applies sentiment analysis to IMDb movie
reviews to support data-driven decision-making in the entertainment industry. The process began with
data pre-processing, including converting text reviews into numerical vectors using Word2Vec. Multiple
machine learning models were developed and fine-tuned to classify review sentiments as positive or
negative, including Logistic Regression, SVM, XGBoost, Random Forest, Decision Tree, and a Multi-
Layer Perceptron (MLP). Among these, the MLP (Neural Network) model achieved the best performance, with optimal
results obtained using Word2Vec embeddings of length 500.

Process
---
Data is downloaded as CSV file to local storage from Kaggle.

Exploratory data analysis was then conducted to inform the steps needed to properly process and clean the data into a usable state.

Data cleaning involved lowercasing, the removal of unwanted text (HTML, URLs, punctiations, emojis, and digits), and removal of stop words.

Pre-processing involved encoding sentiment (positive = 1, negative = 0) and using Word2Vec(skip-a-gram) to transform our text data into numeric vectors that are usable by machine learning models.

Lastly multiple classification models were developed and tuned for optimal hyperparameters using GridSearchCV.

Experimentation with length of vectors used was also explored to find optimal results.

Results
---
**1. Overview:**  The MLP model with two hidden layers of respective sizes 100 and 200 was found to provide the highest classification accuracy, with an F1-Score of .8911. 

Data
---
<img width="336" alt="Image" src="https://github.com/user-attachments/assets/e393f947-9ec9-4086-90b0-4caf4d4cf420" />

EDA
---
![image](https://github.com/user-attachments/assets/8259caaf-c55a-4f92-8bff-ce37321bb9c8)

<img width="855" alt="Screenshot 2025-01-23 at 5 51 04 PM" src="https://github.com/user-attachments/assets/834f9851-4f0d-422f-9df8-9441de1d3d6c" />



Links
---
[Data Source](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data)

