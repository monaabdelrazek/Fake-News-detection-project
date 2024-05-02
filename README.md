# Fake News Detection using AI

This project aims to detect fake news using Artificial Intelligence techniques. The proliferation of fake news has become a significant issue in recent years, with misinformation spreading rapidly across social media platforms and other online sources. This project utilizes machine learning and natural language processing (NLP) to distinguish between real and fake news articles.

## Introduction

The spread of misinformation poses a threat to society, affecting public opinion, political discourse, and even public health. This project addresses this issue by developing a machine learning model capable of identifying fake news articles with high accuracy. By automating the detection process, we aim to assist users in discerning trustworthy sources from unreliable ones.

## Dataset

We use a publicly available dataset containing labeled news articles, classifying them as either real or fake. The dataset is sourced from [https://www.kaggle.com/c/fake-news/data?select=train.csv]. It comprises articles from various domains, including politics, health, and entertainment, to ensure the model's robustness across different topics.

## Methodology

Our approach involves several steps:

1. **Data Preprocessing**: Cleaning and tokenizing the text data, removing stopwords, and performing stemming or lemmatization.
2. **Feature Extraction**: Transforming the text into numerical features using techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) or word embeddings.
3. **Model Training**: Training a machine learning model (e.g., SVM, Random Forest, or Neural Network) on the extracted features to classify news articles as real or fake.
4. **Evaluation**: Assessing the model's performance using metrics like accuracy, precision, recall, and F1-score on a separate test dataset.



