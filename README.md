# March-Machine-Learning-Mania-2026-Kaggle-Solution
Probability forecasts for all possible tournament matchups using an ensemble ML pipeline with calibrated predictions.

📌 Project Overview

This project builds predictive models for NCAA Men’s and Women’s basketball tournaments by learning historical team performance patterns and matchup statistics.
- The solution focuses on:
- Team strength modeling
- Matchup-based feature engineering
- Ensemble machine learning for probability prediction

🧠 Models Used
1. Logistic Regression — Baseline linear classifier
2. LightGBM — Gradient boosting for high-performance predictions
3. Ensemble — Combined predictions for better stability and accuracy

⚙️ Feature Engineering
- Key engineered matchup features:
- Win Percentage Difference
- Average Margin Difference
- Offensive Rating Difference
- Defensive Rating Difference
- Net Rating Difference
- Elo Rating Difference
- Possessions Difference
- Seed Difference
- All features are computed as Team1 − Team2 to capture competitive advantage.

## 🗂️ Project Architecture

```text
.
Data Loading
   ↓
Data Cleaning
   ↓
Feature Engineering (Team Stats → Matchup Differences)
   ↓
Train Models (Men & Women Separate)
   ↓
Generate Predictions
   ↓
Ensemble Predictions
   ↓
Submission File Generation
```

## 🗂️ Project Structure

```text
.
├── data/                # Competition datasets
├── notebooks/           # Kaggle notebooks
├── models/              # Trained models
├── submissions/         # Submission CSV files
└── README.md
```

## 🔮 Future Work
- Add player-level statistics
- Use deep learning models
- Hyperparameter optimization
- Advanced ensemble stacking
- Real-time tournament simulation
