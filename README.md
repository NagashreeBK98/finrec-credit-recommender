# 🏦 FinRec: Fraud-Aware Credit Card Recommendation System

> Personalized fintech recommendations using Collaborative Filtering, Matrix Factorization & Clustering on real-world credit card transaction data.

---

## 📌 Overview

FinRec is a fraud-aware recommendation system that leverages customer credit card transaction behavior to generate **personalized Top-K recommendations** for offers, spending categories, and customer targeting.

This project frames fintech personalization as a recommendation problem — where transaction history serves as implicit user-item interaction data to drive intelligent, behavior-based suggestions.

---

## 🎯 Key Features

- **Fraud-Aware Design** — integrates fraud signals into the recommendation pipeline
- **Multiple Recommendation Models** — from popularity baselines to advanced collaborative filtering
- **Top-K Ranking** — generates ranked personalized recommendations per customer
- **End-to-End Pipeline** — data preprocessing → EDA → modeling → evaluation

---

## 🗂️ Project Structure

```
finrec-credit-recommender/
├── notebook/
│   └── FinRec_Recommendation_System.ipynb   # Full pipeline: EDA, models, evaluation
├── report/
│   └── FinRec_Project_Report.pdf            # Final project report
├── data/
│   └── .gitkeep                             # Dataset not included (see below)
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📊 Dataset

**Source:** [Kaggle – Credit Card Transactions Dataset](https://www.kaggle.com/datasets/priyamchoksi/credit-card-transactions-dataset)

Real-world credit card transaction records capturing customer spending behavior across merchants, categories, locations, and time periods.

Key attributes:
- Customer identifiers
- Transaction amount & frequency
- Merchant & transaction category
- Transaction time & location
- Payment & behavioral patterns

> ⚠️ Dataset not included in this repo due to size. Download directly from Kaggle link above and place in `data/`.

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python 3.10 |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn, SciPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 🤖 Models Implemented

| Model | Type |
|---|---|
| Popularity-Based | Baseline |
| Frequency-Based Ranking | Baseline |
| Collaborative Filtering | Learning-Based |
| Matrix Factorization | Learning-Based |
| Clustering-Based Segmentation | Learning-Based |

---

## 📈 Evaluation Metrics

- Precision@K
- Recall@K
- F1 Score
- NDCG (Normalized Discounted Cumulative Gain)

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone git@github.com:NagashreeBK98/finrec-credit-recommender.git
cd finrec-credit-recommender

# Install dependencies
pip install -r requirements.txt

# Launch notebook
jupyter notebook notebook/FinRec_Recommendation_System.ipynb
```

---

## 🔗 Related Project

This project is part of a **two-project fintech series** using the same credit card transaction dataset:

| Project | Focus |
|---|---|
| [fraudshield-mlops](https://github.com/NagashreeBK98/fraudshield-mlops) | Fraud Detection — XGBoost + Docker + MLOps |
| **finrec-credit-recommender** (this repo) | Recommendation System — CF + Matrix Factorization |

> Same dataset, different ML problems — demonstrating versatility across classification and recommendation domains.

---

## 👩‍💻 Author

**Nagashree Bommenahalli Kumaraswamy**  
MS Data Analytics Engineering, Northeastern University  
[GitHub](https://github.com/NagashreeBK98) | [LinkedIn](https://linkedin.com/in/nagashreebk)

---

## 📚 Course

IE7275 – Data Mining in Engineering | Spring 2026 | Northeastern University
