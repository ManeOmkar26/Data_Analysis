# 📊 Data Analysis Projects — Omkar Mane

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
</p>

<p align="center">
  <b>End-to-end data analysis and machine learning projects covering EDA, classification, and business insight generation.</b><br/>
  Built as part of the Google Advanced Data Analytics Professional Certificate (2026).
</p>

---

## 📁 Projects at a Glance

| # | Project | Domain | Key Techniques | Notebook |
|---|---------|--------|----------------|----------|
| 1 | Waze User Churn Prediction | Mobility / Navigation | EDA · Decision Tree · Random Forest · XGBoost | [View →](./Waze_User_churn_analysis.ipynb) |
| 2 | TikTok Claim Classification | Social Media | EDA · Logistic Regression · Classification | [View →](./TikTok_analysis.ipynb) |
| 3 | Fitbit Health Band Analysis | Health & Wearables | EDA · User Segmentation · Trend Analysis | [View →](./FITBIT_analysis.ipynb) |
| 4 | Transportation Data Analysis | Urban Mobility | EDA · KPI Reporting · Statistical Analysis | [View →](./Transportation_analysis.ipynb) |

---

## 🔁 Project 1 — Waze User Churn Prediction

> **Business Problem:** Predict which users are likely to stop using the Waze navigation app so the product team can act proactively to retain them.

### What I Did
- Performed comprehensive **Exploratory Data Analysis (EDA)** on user behavioral data — activity frequency, sessions, drive counts, and days since last active
- **Engineered features** from raw activity logs to capture short-term and long-term usage trends
- Built and compared **three classification models**: Decision Tree, Random Forest, and XGBoost
- Evaluated performance using **F1-score, Precision, Recall, and AUC-ROC** to handle class imbalance

### Key Findings
- Users with high session frequency in the last 30 days had significantly lower churn probability
- Power users (high lifetime drives, consistent monthly activity) were the most retained segment
- XGBoost delivered the best predictive performance across all evaluation metrics
- Feature importance analysis revealed `activity_days` and `sessions` as top churn indicators

### Tools & Libraries
`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `XGBoost` · `Matplotlib` · `Seaborn`

---

## 📹 Project 2 — TikTok Claim Classification

> **Business Problem:** Automate classification of user-submitted video content as "claim" or "opinion" to scale TikTok's content moderation pipeline.

### What I Did
- Cleaned and preprocessed raw TikTok video submission metadata (views, likes, shares, comment counts)
- Conducted **EDA** to understand class distribution and feature relationships
- Built a **Logistic Regression classifier** to predict whether a video contains a verifiable claim or subjective opinion
- Iterated on **feature selection** and threshold tuning to optimize for precision vs. recall trade-off

### Key Findings
- Video engagement metrics (view count, like ratio, share count) were the strongest predictors of claim type
- Claim videos tend to receive higher engagement but more polarized reactions than opinion videos
- The classification model achieved strong accuracy, enabling large-scale automated pre-screening
- Automating this pipeline could significantly reduce manual moderator review workload

### Tools & Libraries
`Python` · `Pandas` · `Scikit-learn` · `Matplotlib` · `Seaborn`

---

## ❤️ Project 3 — Fitbit Health Band Analysis

> **Business Problem:** Analyze wearable device usage data to uncover user behavior patterns and generate actionable recommendations for Fitbit's marketing and product teams.

### What I Did
- Analyzed **daily activity logs**: step counts, active minutes, calorie burn, distance, and sleep duration
- **Segmented users** by activity intensity (sedentary, lightly active, fairly active, very active)
- Identified **peak usage hours** and day-of-week activity trends
- Correlated sleep quality with activity levels and device engagement rates
- Translated statistical findings into **concrete business recommendations**

### Key Findings
- Only ~25% of tracked users consistently met the recommended 10,000 steps/day goal
- Most users averaged below the recommended 8 hours of sleep per night
- High sedentary time strongly correlated with lower device engagement and feature usage
- Tuesday–Thursday showed the highest activity levels; weekends showed significant drop-offs
- **Recommendation:** Target low-activity segments with personalized nudges and gamification features

### Tools & Libraries
`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`

---

## 🚌 Project 4 — Transportation Data Analysis

> **Business Problem:** Analyze urban transportation data to surface key operational KPIs and identify patterns that can inform service and resource allocation decisions.

### What I Did
- Cleaned and aggregated trip-level transportation data, handling missing values and outliers
- Computed **key performance indicators**: trip volume, revenue metrics, distance distributions, peak demand windows
- Built visualizations to surface **temporal patterns** (time-of-day, day-of-week demand curves)
- Delivered actionable insights for operational decision-making

### Key Findings
- Demand peaks sharply during morning (7–9 AM) and evening (5–7 PM) commute windows
- Identified high-revenue routes and underutilized service corridors
- Weekend demand patterns differ significantly from weekday — suggesting separate scheduling strategies

### Tools & Libraries
`Python` · `Pandas` · `Matplotlib` · `Seaborn`

---

## 🛠️ Full Tech Stack

### Languages & Core Libraries
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

### Machine Learning
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat)

`Logistic Regression` · `Decision Tree` · `Random Forest` · `XGBoost` · `Feature Engineering` · `Pipeline Building` · `Cross-Validation`

### Data Analysis & Statistics
`EDA` · `Hypothesis Testing` · `Statistical Analysis` · `User Segmentation` · `KPI Reporting` · `A/B Testing concepts`

### Visualization
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)

### Environment
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)

---

## ▶️ How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/ManeOmkar26/Data_Analysis.git
cd Data_Analysis

# 2. Install required libraries
pip install pandas numpy scikit-learn matplotlib seaborn xgboost jupyter

# 3. Launch Jupyter Notebook
jupyter notebook

# 4. Open any .ipynb file from the file browser
```

> **Python version:** 3.8+ recommended

---

## 📂 Repository Structure

```
Data_Analysis/
│
├── data/                              # Raw datasets
│
├── Waze_User_churn_analysis.ipynb     # Churn prediction — Decision Tree, XGBoost
├── TikTok_analysis.ipynb              # Claim classification — Logistic Regression
├── FITBIT_analysis.ipynb              # Health data EDA — User segmentation
├── Transportation_analysis.ipynb      # Urban mobility KPI analysis
│
└── README.md
```

---

## 📜 Certificate Context

These projects were completed as capstone work for the:
- 🎓 **Google Advanced Data Analytics Professional Certificate** — Google / Coursera (2026)
- 🎓 **Google Data Analytics Professional Certificate** — Google / Coursera (2026)

---

## 📬 Connect With Me

I'm actively seeking **Data Analyst / Analytics roles in India**. Let's connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Omkar%20Mane-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omkar-mane-7b7b84194)
[![Email](https://img.shields.io/badge/Email-maneomkar23%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maneomkar23@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-ManeOmkar26-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ManeOmkar26)

---

<p align="center"><i>"Turning raw data into decisions — one dataset at a time."</i></p>
