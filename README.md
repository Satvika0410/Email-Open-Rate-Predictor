# 📩 Email Open Rate Predictor

An interactive Streamlit-based machine learning app that predicts the likelihood of an email being opened, based on its subject line, content, structure, and metadata. It also uses NLP and SHAP explainability to guide improvements.

---

## 🚀 Features

- Predicts whether an email is likely to be opened or ignored.
- Uses **XGBoost** with engineered features and grid search tuning.
- **Sentiment analysis** using VADER to score subject line "hotness".
- Keyword suggestions to improve weak subject lines.
- **SHAP-based model explanations** for every prediction.
- Clean and responsive **Streamlit UI**.

---

## 🧠 Technologies Used

- Python 3.10+
- pandas, numpy, scikit-learn, xgboost
- NLTK (`SentimentIntensityAnalyzer`)
- SHAP (SHapley Additive exPlanations)
- Streamlit for the web app
- Joblib for model persistence

---

## 📁 Project Structure
