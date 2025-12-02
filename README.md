# CodSoft_Internship_Tasks
Projects and assignments completed during CodSoft Data Science Internship, including data analysis, visualization, and machine learning implementations.


# Data Science Internship Projects

This repository contains four modular machine learning projects developed for internship review. Each project demonstrates end‑to‑end workflows including preprocessing, feature engineering, model training, evaluation, and reproducible pipelines.

# 🚀 Projects Overview
| 🚢 **Titanic Survival Prediction** | Predicts passenger survival on the Titanic dataset. | Classification models, feature engineering, handling missing values, logistic regression, decision trees. |
| 🎬 **Movie Rating Prediction** | Predicts user ratings for movies based on metadata and user behavior. | Regression modeling, feature encoding, train‑test split, evaluation metrics (RMSE, MAE). |
| 💳 **Credit Card Fraud Detection** | Classifies transactions as fraudulent or legitimate. | Imbalanced dataset handling (SMOTE/undersampling), precision‑recall analysis, ROC‑AUC. |
| 📈 **Sales Prediction** | Predicts product sales based on advertising spend and other features. | Linear regression, feature importance, residual analysis, visualization. |

# 🛠️ Project Structure

```

├── titanic_survival/
│   ├── data/
│   ├── preprocessing.py
│   ├── modeling.py
│   ├── evaluation.py
│   └── main.py

├── movie_rating/
│   ├── data/                # Raw & processed datasets
│   ├── preprocessing.py     # Cleaning, encoding, feature engineering
│   ├── modeling.py          # Model training & evaluation
│   ├── evaluation.py        # Metrics & visualization
│   └── main.py              # Pipeline runner

├── credit_card_fraud/
│   ├── data/
│   ├── preprocessing.py
│   ├── modeling.py
│   ├── evaluation.py
│   └── main.py

├── sales_prediction/
│   ├── data/
│   ├── preprocessing.py
│   ├── modeling.py
│   ├── evaluation.py
│   └── main.py

├── common/
│   ├── utils.py             # Shared helper functions
│   └── config.py            # Configurations & constants

├── requirements.txt         # Dependencies
└── README.md                # Project documentation
```



# ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/internship-projects.git
cd internship-projects
pip install -r requirements.txt
```

# ▶️ Usage

Run any project pipeline:

```bash
# Movie rating prediction
python movie_rating/main.py

# Titanic survival prediction
python titanic_survival/main.py

# Credit card fraud detection
python credit_card_fraud/main.py

# Sales prediction
python sales_prediction/main.py
```

# 📊 Evaluation Metrics
  
- **Titanic Survival Prediction:** Accuracy, Precision, Recall, F1‑score  
- **Movie Rating Prediction:** RMSE, MAE, R²
- **Credit Card Fraud Detection:** Precision, Recall, F1‑score, ROC‑AUC  
- **Sales Prediction:** R², Adjusted R², Residual plots  


# 📌 Notes for Reviewers

- Each project is modularized into **preprocessing, modeling, and evaluation scripts**.  
- Code logic matches notebook workflows for transparency and reproducibility.  
- Shared utilities are placed in the `common/` folder for consistency.  
- All datasets are either synthetic or publicly available.  

# 👨‍💻 Author

Developed by **Drashtanta** as part of internship submissions.  
Focus: clarity, reproducibility, and professional project presentation.  
