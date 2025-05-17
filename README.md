# 🚨 Fake News Detection System

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3%2B-orange)
![Docker](https://img.shields.io/badge/Docker-Containers-blue?logo=docker)

An NLP-powered system that classifies news articles as real or fake using TF-IDF and Naive Bayes, containerized for easy deployment.

## 🌟 Features

- **Text Analysis**: TF-IDF with n-gram features
- **Machine Learning**: Multinomial Naive Bayes classifier
- **Containerized**: Ready-to-run Docker image
- **REST API**: (Optional) Flask endpoint support
- **Performance**: 92%+ accuracy on test data

## 🛠️ Installation

### Option 1: Local Setup
```bash
git clone https://github.com/yourusername/fake-news-detector.git
cd fake-news-detector
pip install -r requirements.txt
python -m nltk.downloader stopwords wordnet