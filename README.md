# 🏏 IPL 2025 Prediction — Match & Toss Winner Forecasting

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)
![License](https://img.shields.io/badge/license-MIT-green)
![ML](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-lightgrey)

This repository contains a complete machine learning pipeline to forecast **Toss Winners** and **Match Winners** for the **IPL 2025** season. It uses historical IPL data from 2008–2023 and generates match-by-match predictions along with storytelling-style explanations.

---

## 📁 Project Structure

```
📦 IPL-2025-Prediction
├── matches.csv                       # Historical match-level data
├── deliveries.csv                    # Historical ball-by-ball data
├── IPL-Season-Schedule-2025.csv      # Cleaned match schedule for 2025
├── IPL_2025_Storytelling_Report.md   # Markdown with match-by-match predictions & insights
├── IPL_2025_Match_Storytelling_Generator.py  # Script to generate the report
└── README.md                         # This file
```

---

## 📊 Features

- Predict toss winners using toss trends and venue/captain history
- Predict match winners using:
  - Historical team performance
  - Toss results
  - Venue-specific advantages
  - Batting vs bowling trends
- Generate a Markdown report with:
  - Match insights
  - Model rationale
  - Head-to-head stats
  - Toss and chasing advantages

---

## 🚀 How to Use

```bash
# Clone the repository
git clone https://github.com/yourusername/ipl-2025-prediction.git
cd ipl-2025-prediction

# (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the script to generate match predictions
python IPL_2025_Match_Storytelling_Generator.py
```

---

## 📈 Visualizations

The project also includes:
- Bar and line plots for team trends
- Heatmaps for win distribution
- Cumulative win graphs for 2025 predictions

---

## 🧠 ML Model

- RandomForestClassifier (sklearn)
- Categorical encoding for team/venue/toss_winner
- Feature engineering: win %, toss %, avg scores, venue win rate

---

## 📝 License

This project is licensed under the MIT License.

---

## 🙌 Credits

Created as part of a Major Capstone Project by [Sanket Parmar]  
Built using data from [Kaggle IPL Dataset](https://www.kaggle.com/datasets)

---

