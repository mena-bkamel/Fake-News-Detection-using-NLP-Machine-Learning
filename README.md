# 📰 Fake News Detection using NLP & Machine Learning

This project is an end-to-end Fake News Detection system that uses Natural Language Processing (NLP) and a Naive Bayes classifier to classify news articles as either **Real** or **Fake**. It combines standard text preprocessing techniques with TF-IDF vectorization and machine learning for accurate classification.

---

## 📌 Project Features

- ✅ Data cleaning & preprocessing (lowercase, punctuation removal, stopwords, lemmatization)
- ✅ Feature extraction using TF-IDF with n-grams
- ✅ Model training using Multinomial Naive Bayes
- ✅ Model evaluation: accuracy, confusion matrix, classification report
- ✅ Reusable prediction function for new inputs
- ✅ Sample predictions on custom headlines

---

## 🧠 Technologies Used

- **Python**
- **Pandas**, **NumPy** – data handling
- **NLTK** – text preprocessing
- **Scikit-learn** – TF-IDF, machine learning models, evaluation
- **Matplotlib**, **Seaborn** – visualization

---

## 📂 Dataset

The dataset consists of two parts:

- `True.csv` – real news articles
- `Fake.csv` – fake news articles

Each entry includes:
- `title`: Headline of the article
- `text`: Full content of the article
- `label`: 0 (Real) or 1 (Fake)

These datasets are combined and shuffled before training.

---

## 📊 Model Workflow

1. **Data Merging & Cleaning**
2. **Text Preprocessing**:
   - Convert to lowercase
   - Remove punctuation
   - Remove stopwords
   - Lemmatize words
3. **TF-IDF Vectorization**
4. **Train-Test Split**
5. **Model Training** with Multinomial Naive Bayes
6. **Evaluation**:
   - Accuracy score
   - Confusion matrix (heatmap)
   - Classification report (precision, recall, F1)
7. **Custom Prediction Function**
   - Use `predict_news(text)` to classify any news headline or content

---

## 📌 Example: Sample Predictions

```python
sample_news = [
    "Scientists confirm chocolate prevents cancer",
    "Congress passes new budget bill unanimously",
    "Aliens establish embassy in Washington",
    "Federal Reserve raises interest rates by 0.25%"
]

for news in sample_news:
    print(f"{news} → {predict_news(news)}")
```
## 🚀 Getting Started
### 1. Clone the repository
```bash
    git clone https://github.com/yourusername/fake-news-detector.git
    cd fake-news-detector
```
### 2. Install dependencies
```bash
  pip install -r requirements.txt
```
### 3. Run the script or Jupyter Notebook
Follow along in `notebooks/fake_news_detection.ipynb` 

## 🔗 Contact
### Created by: Mina Bebawy
💼 [My Upwork Profile](https://www.upwork.com/freelancers/~01a15f0b82750ad98d)

💼 [My Fiverr Profile](https://www.fiverr.com/mena_bebawy)

📧 [E-mail](copperbox22@gmail.com)

## 📃 License
#### This project is licensed under the MIT License – see the LICENSE file for details.


