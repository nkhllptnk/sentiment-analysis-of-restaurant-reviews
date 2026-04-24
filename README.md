# 🍽️ Majhitar Restaurant Sentiment Analysis & Recommendation System

## 📌 Overview
This project performs Sentiment Analysis on Google reviews of restaurants in Majhitar, Sikkim using Natural Language Processing (NLP).

It also includes a **dish-based recommendation system** where users can search for a dish (e.g., momo, coffee) and get the best restaurants based on review sentiment.

---

## 🎯 Key Features
- Sentiment Analysis using VADER (rule-based NLP)
- Restaurant ranking based on average sentiment score
- Dish-based recommendation system
- Data visualization (bar charts, pie charts, stacked graphs)
- Model evaluation (Accuracy, Precision, Recall, F1-score, Confusion Matrix)

---

## 📊 Dataset
- 205 reviews from 21 restaurants
- Collected manually from Google Maps
- Columns:
  - `restaurant_name`
  - `review`

---

## 🧠 NLP Pipeline

1. Data Collection (Google Reviews CSV)
2. Preprocessing (cleaning, handling nulls)
3. VADER Sentiment Scoring
4. Sentiment Classification (Positive / Negative / Neutral)
5. Aggregation (average score per restaurant)
6. Visualization
7. Dish-Based Recommendation System
8. Model Evaluation

---

## 🍜 Recommendation System

User Input:
I want: momo

System:
- Filters reviews containing "momo"
- Computes sentiment score for those reviews
- Ranks restaurants based on dish-specific sentiment

---

## 📈 Results
- Accuracy: 95%
- Precision: 100%
- Recall: 91.67%
- F1 Score: 95.65%

---

## 📸 Outputs
- Sentiment Score per Restaurant
- Sentiment Breakdown Chart
- Overall Sentiment Distribution
- Confusion Matrix

---

## 🚀 How to Run

1. Clone the repository:
git clone https://github.com/nkhlptnk/sentiment-analysis-of-restaurant-reviews.git⁠

2. Install dependencies:
pip install -r requirements.txt

3. Run the notebook:
jupyter notebook
---

## 📂 Project Structure

sentiment_project/ │ ├── data/ ├── notebooks/ ├── outputs/ ├── ppt/ ├── README.md ├── requirements.txt

---

## 🔮 Future Scope
- Use BERT / Transformer models
- Add multilingual support (Hindi/Nepali)
- Build a web app (Streamlit/Flask)
- Automate data collection

---

## 👤 Author
**Nikhil Patnaik**


