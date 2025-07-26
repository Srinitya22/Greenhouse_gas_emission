
# 🌍 Greenhouse Gas Emission Analysis – Week 1 Internship Project

This project focuses on analyzing supply chain greenhouse gas (GHG) emissions across various U.S. industries using the 2015 emission factors dataset.

## 📊 Objective
To identify and visualize the top industries with the highest supply chain GHG emission factors (including margins), using data analysis and visualization techniques in Python.

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## 🔍 What’s Included
- `Week1_GHG_Analysis.ipynb` – Colab notebook with code to load, process, and visualize the dataset.
- `SupplyChainEmissionFactorsforUSIndustriesCommodities2015_Summary.csv` – Dataset used for the analysis.

## ✅ Key Insights
- Top 10 industries were identified based on total supply chain emission factors (with margins).
- A bar chart visualizes the highest-emitting industries for better understanding and presentation.

## ✍️ Improvisations Made
- Cleaned column names for accuracy.
- Identified actual column labels from the dataset.
- Used clear visualizations with titles and axis formatting.
- Organized code into logical, readable sections.

---

## 🌱 Week 2 Progress – Model Building & Evaluation

Trained and fine-tuned a Random Forest Regressor using industry-level GHG emission data. Scaled features, evaluated performance using RMSE and R², and saved the best model for future predictions.

### 🔧 Tools/Libraries Added

* Scikit-learn
* Joblib
* StandardScaler
* GridSearchCV

### ✅ Achievements

* Cleaned and preprocessed numeric features.
* Tuned hyperparameters using GridSearchCV (best: `n_estimators=200`, `max_depth=10`).
* Evaluated model performance (R², RMSE).
* Exported final model and scaler with Joblib.
