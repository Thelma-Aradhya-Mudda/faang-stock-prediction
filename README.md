# 📈 Financial News Analyzer & Stock Movement Predictor

This project predicts the next-day stock movement (Up/Down) for FAANG companies by combining financial news sentiment analysis and time-series modeling. It is built in two phases:

- 🔍 **Phase 1**: Fine-tunes a BERT model to classify news headlines as Positive, Neutral, or Negative.
- 📉 **Phase 2**: Engineers features from 5 years of historical stock data and trains a model to predict next-day movement.

---

## 🎯 Project Motivation

Stock markets are influenced not just by technical data but also by how the media and public interpret news. This project aims to merge:
- **Quantitative signals** (historical stock prices)
- **Qualitative sentiment** (news headlines)  
…to create a more accurate and interpretable market predictor for major FAANG stocks.

---

## 🚀 Features

- 📚 Fine-tuned BERT-based classifier for real-time financial sentiment
- ⏳ Time-series feature engineering (moving averages, RSI, etc.)
- 📊 Random Forest model for binary classification (Up/Down)
- 🧩 FAANG Stock Support: AAPL, AMZN, GOOGL, NFLX, META
- 📅 30-day trend visualizations & predicted movements
- 🛠️ Fully annotated Jupyter Notebook and customizable pipeline

---

## 🧠 Technologies Used

| Category      | Tools/Frameworks                                  |
|---------------|---------------------------------------------------|
| Programming   | Python                                             |
| NLP           | HuggingFace Transformers (BERT), NLTK             |
| ML Models     | Random Forest Classifier, Scikit-learn            |
| Data Handling | Pandas, yFinance                                   |
| Visualization | Matplotlib                                        |

---

## ✅ Sample Output (April 17, 2025)

| Stock | Sentiment | Confidence |
|-------|-----------|------------|
| AAPL  | 🔽 Down   | 74%        |
| AMZN  | 🔽 Down   | 61%        |
| GOOGL | 🔽 DOWN   | 51%        |
| NFLX  | 🔽 Down   | 61%        |
| META  | 🔽 Down   | 71%        |

---

## ▶️ How to Run

```bash
# Step 1: Clone this repo
git clone https://github.com/your-username/faang-stock-prediction.git

# Step 2: Install requirements
pip install yfinance transformers scikit-learn matplotlib pandas

# Step 3: Open the notebook
jupyter notebook Financial_News_Analyzer_&_Stock_Movement_Predictor.ipynb
