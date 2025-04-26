Fake News Detection - Project Overview
This project builds a machine learning model that automatically classifies news articles as real or fake. It follows a complete machine learning workflow:

Data Loading: The dataset is sourced from [Fake and Real News Dataset on Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset).

Data Preprocessing: Text articles are cleaned and transformed into numerical feature vectors using TF-IDF (Term Frequency-Inverse Document Frequency).

Data Splitting: The dataset is divided into training and testing sets to properly validate the model's performance.

Model Training: A Logistic Regression classifier is trained on the TF-IDF features to learn patterns distinguishing fake news from real news.

Model Evaluation: The model’s performance is measured using accuracy on the unseen test set.

By the end of this notebook, a simple yet effective machine learning model is created that can predict the authenticity of a news article based on its text content.
