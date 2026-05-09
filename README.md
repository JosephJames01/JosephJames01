# Hi, I'm Joe Harding 👋

**MSc Financial Technology @ University of Exeter (78%) | Research Assistant to Prof. Julian Jamison (Oxford GPI · MIT J-PAL · fmr. World Bank) | BEng Robotics Engineering — First Class Honours**

I build end-to-end data science systems — from causal inference pipelines on international RCTs to deployed ML applications. Background in robotics engineering gives me a systems-level perspective on how models live in the real world.

---

## 📌 Featured Projects

### 🔬 Research — Causal Inference (Co-authored with Prof. Julian Jamison)
Co-authoring a causal inference paper with Prof. Julian Jamison — Oxford Global Priorities Institute, MIT J-PAL, and former World Bank Senior Economist.
- Pre-registered 3-country RCT (N=3,124; Nigeria & India) testing whether cognitive framing shifts normative policy preferences
- Engineered full Python data pipeline: 3 Qualtrics exports (N_raw=3,731 → 3,124), multi-source merge, IQR outlier removal, attention-check exclusion, recoding of 108 variables
- Causal estimation: logistic & ordered logistic regression with robust SEs, covariate-adjusted balance checks (chi-square/Kruskal-Wallis) across 20 outcomes

---

### 📈 Time Series Forecasting — Kaggle Competition (Top 10%)
*[In progress — deploying June 2026]*
End-to-end time series forecasting system targeting top 10% on a Kaggle competition leaderboard.
- Feature engineering: Fourier transforms for seasonality decomposition, Markov Switching model for regime detection
- Ensemble model: XGBoost/LightGBM with cross-validated hyperparameter tuning
- Deployed via Flask + GitHub Actions for live inference
- Full mathematical derivations in README (Fourier basis, HMM transition matrices, gradient boosting objective)
- **Stack:** Python, pandas, statsmodels, XGBoost, LightGBM, Flask, GitHub Actions

---

### 📊 UK Household Savings — Econometric Panel Analysis
[Econometrics-FE →](https://github.com/JosephJames01/Econometrics-FE)
- Two-way fixed effects panel regression (N=540, n=90, T=6) with three-way interactions (income × family × gender)
- Pre-post first-differences estimator (2016→2017) isolated £2,924 government savings incentive shock
- Key drivers: income (β=0.734, p=0.006), prior savings (β=0.139, p<0.001) under robust HC1 clustered SEs
- Validated model specification via nested pFtest (p=0.455); confirmed time FE joint significance (p=0.004)
- **Stack:** R, plm, AER, sandwich (vcovHC), stargazer, ggplot2

---

### 🤖 Credit Card Fraud Detection — End-to-End ML System
[credit-card-fraud →](https://github.com/JosephJames01/credit-card-fraud)
- MLP classifier on severely imbalanced transaction data; SMOTE for minority class oversampling
- GridSearchCV hyperparameter tuning; F1=0.77 on held-out test set
- Deployed via Flask + Railway for real-time predictions
- **Stack:** Python, scikit-learn, pandas, NumPy, Flask, HTML/CSS, Railway

---

### ⏱️ Ultra-Low-Latency Athletics Timing System
[SprintTiming →](https://github.com/JosephJames01/SprintTiming)
- Hardware + software system for professional sprint timing with sub-millisecond precision
- Wireless sensor architecture with real-time data transmission
- **Stack:** C++, Arduino, embedded systems

---

## 🛠️ Skills

**Languages:** Python · R · SQL · JavaScript · C++ · MATLAB · Bash  
**ML/DS:** scikit-learn · XGBoost · LightGBM · statsmodels · pandas · NumPy · imbalanced-learn  
**Deployment:** Flask · GitHub Actions · Docker · Railway  
**Econometrics:** Panel regression · Causal inference · RCT design · Fixed effects · IV estimation  
**Other:** Git/GitHub · ROS · HTML/CSS

---

## 📚 Currently

- 🔬 Finalising co-authored causal inference paper with Prof. Jamison
- 



---
