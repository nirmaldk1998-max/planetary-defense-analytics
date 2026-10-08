# 🪐 Planetary Defense Analytics: Classifying, Predicting & Clustering Asteroids

## 📌 Project Overview
An end-to-end Machine Learning pipeline built on the NASA Asteroid/Small-Body dataset to classify Potentially Hazardous Asteroids (PHAs), predict physical diameter from orbital characteristics, and discover natural orbital families using clustering algorithms.

## 🚀 Key Features & Performance Metrics

### Case 1: Classification (PHA Status)
- **Best Model:** Gradient Boosting / Random Forest (Class Weight Balanced)
- **Key Metrics:** Precision: `91.6%`, Recall: `100%`, F1-Score: `0.956`, ROC-AUC: `0.9999`

### Case 2: Regression (Diameter Prediction)
- **Best Model:** Random Forest Regressor
- **Key Metrics:** $R^2$ Score: `0.892`, RMSE: `3.626` km, MAE: `1.271` km

### Case 3: Clustering (Orbital Grouping)
- **Algorithms:** K-Means (k=3) & DBSCAN
- **Silhouette Score:** K-Means: `0.137`, DBSCAN: `0.161`

---

## 🛠️ Tech Stack
- **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, SHAP, Joblib
- **Visualization:** Matplotlib, Seaborn
- **Deployment:** Streamlit Dashboard

## 💻 How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/planetary-defense-analytics.git](https://github.com/your-username/planetary-defense-analytics.git)
   cd planetary-defense-analytics
