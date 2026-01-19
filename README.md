# 🎯 Candidate Screening Predictor

An AI-powered web application that predicts whether a candidate's profile will be **screened IN or OUT** for AI/ML roles. Built with Streamlit, SHAP explainability, and Gemini AI for natural language explanations.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)
![Model Accuracy](https://img.shields.io/badge/Accuracy-99.89%25-green.svg)

## 🚀 Features

- **ML-Powered Predictions** - Random Forest model trained on 4,500+ candidate profiles
- **SHAP Explainability** - Visual breakdown of which factors influenced the prediction
- **AI-Generated Insights** - Gemini AI provides detailed explanations and recommendations
- **Modern UI** - Dark theme with teal/amber gradient design, glassmorphism effects
- **Real-time Analysis** - Instant predictions with confidence scores

## 📊 How It Works

1. **Enter your profile details** - Experience, education, current role, portfolio
2. **Select your technical skills** - Choose from 50 AI/ML-related skills
3. **Get instant prediction** - See if you'd be screened IN or OUT
4. **Understand why** - SHAP values show feature impact with AI explanation

## 🛠️ Tech Stack

- **Frontend**: Streamlit with custom CSS
- **ML Model**: Random Forest Classifier (scikit-learn)
- **Explainability**: SHAP (SHapley Additive exPlanations)
- **AI Explanations**: Google Gemini API
- **Feature Engineering**: TF-IDF for skills vectorization

## 📦 Installation

```bash
# Clone the repository
git clone [https://github.com/Ryanrezzz/CandidateScreeningPredictor.git](https://github.com/Ryanrezzz/CandidateScreeningPredictor.git)
cd CandidateScreeningPredictor

# Install dependencies
pip install streamlit pandas numpy joblib shap matplotlib google-generativeai

# Run the app
streamlit run app.py
