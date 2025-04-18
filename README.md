# 📊 Financial News Analyzer & Stock Movement Predictor

This project combines NLP and machine learning to analyze financial news sentiment and predict whether FAANG stocks (Meta, Apple, Amazon, Netflix, Google) will go up or down the next day.

---

## 🔍 Features

- 🧠 Fine-tuned BERT model on financial news headlines (Phase 1)
- 📉 Time-series model trained on 5 years of stock data (Phase 2)
- ✅ FAANG coverage: AAPL, GOOGL, AMZN, NFLX, META
- 📊 Custom visualizations of trends and predictions 
- 🔮 Forecasts for April 17, 2025

---

## 💼 Technologies Used

- Python, Pandas, Scikit-learn, yFinance
- BERT (transformers), Matplotlib
- Random Forest Classifier

---

## 📌 Prediction Output

| Stock | Prediction  | Confidence |
|-------|------------ |------------|
| AAPL  | 🔽 Down     | 74%        |
| AMZN  | 🔽 Down     | 61%        |
| GOOGL | 🔽 DOWN     | 51%        |
| NFLX  | 🔽 Down     | 61%        |
| META  | 🔽 Down     | 71%        |

---

## 📁 Files

- `Financial_News_and_Stock_Movement_Prediction.ipynb` – Main notebook
- `README.md` – This file


---

## 🚀 How to Run

```bash
pip install yfinance transformers scikit-learn matplotlib
