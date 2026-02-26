# 📰 Fake News Detection using NLP
A complete end-to-end NLP project to classify news articles as **real** or **fake**, using text preprocessing, TF-IDF feature extraction, and a Multinomial Naive Bayes classifier.

---

## 📌 Project Overview
This project demonstrates how Natural Language Processing can be used to detect misinformation. It covers the full pipeline:
- Data loading & labeling
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- TF-IDF vectorization
- Model training (Multinomial Naive Bayes)
- Evaluation (Confusion Matrix, ROC Curve, Metrics)
- Error analysis

Final model accuracy: **93.7%**

---

## 📂 Repository Structure
```fake-news-detection-nlp
│── README.md
│── data/
│── notebooks/
│── src/
│── visuals/
│── requirements.txt
```
---

## 🧠 Tech Stack
- Python
- Pandas, NumPy
- NLTK
- Scikit-Learn
- Matplotlib, Seaborn
- WordCloud

---

## 🔧 How to Run the Project

### Clone the repository
git clone https://github.com/Devenzz/True_Fake_News_Detection-NLP.git

### Navigate to project folder
cd True_Fake_News_Detection-NLP

# Install dependencies
pip install -r requirements.txt

# Open notebook
jupyter notebook notebooks/Fake_News_Detection.ipynb

---

## 📊 Model Performance
- Accuracy: 93.7%
- Model: Multinomial Naive Bayes
- Vectorizer: TF-IDF
- Dataset Size: 44,000+ articles

Visuals included:
- Confusion Matrix
- ROC Curve
- Word Clouds
- EDA Graphs

---

## 🧩 Key Learnings
- Text cleaning improves model accuracy significantly
- Fake news uses more emotional/common vocabulary
- TF-IDF is powerful for text classification
- Naive Bayes is lightweight yet highly effective

---

## 🙌 Contributions
Pull requests and suggestions are welcome!

---

## ⭐ Show Your Support
If you find this project useful, please give it a ⭐ on GitHub!
```
