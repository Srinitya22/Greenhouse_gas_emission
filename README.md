# 🔗 Supply Chain Emission Factor Analysis Using Machine Learning & Data Quality Metrics 📊🌱

An end-to-end data science project focused on analyzing and predicting supply chain emission factors (with margins) across various U.S. industries and commodities. This project uses historical environmental data, machine learning models, and feature engineering to support sustainable, data-driven supply chain decisions.

---

## 🎯 Objective

To build a regression-based predictive model that estimates supply chain emission factors using descriptive variables and data quality indicators such as substance, unit, reliability, and temporal/geographical/technological/data collection correlations.

---

## 🔍 Features

* Analyze multi-year emission data (2010–2016) categorized by industry and commodity
* Clean and preprocess real-world environmental datasets
* Visualize key categorical features (e.g., Source, Unit, Substance)
* Train and evaluate multiple regression models
* Tune model hyperparameters using `GridSearchCV`
* Save and reuse the best-performing model with `joblib`
* Identify key features influencing emission predictions
* Well-documented, modular Jupyter Notebooks with professional visualizations

---

## 🛠️ Technologies Used

* **Python 3** – Core programming language
* **Pandas** – Data cleaning and manipulation
* **NumPy** – Numerical operations
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Machine learning models and evaluation tools
* **Joblib** – Model saving and loading
* **Google Colab** – Cloud-based development environment

---

## ⚙️ How It Works

1. **Load and Combine** multi-year Excel datasets (2010–2016)
2. **Preprocess** the data by handling missing values and encoding categorical variables
3. **Scale** numerical features using `StandardScaler`
4. **Split** the dataset into training and testing subsets
5. **Train** regression models (Random Forest, Gradient Boosting, Linear Regression)
6. **Tune** the Random Forest model using `GridSearchCV`
7. **Evaluate** model performance using RMSE and R²
8. **Export** the best model and scaler using `joblib`

---

## ✅ Final Model Performance

After training and tuning, the best-performing model (Random Forest Regressor) achieved the following results on the test set:

* **Root Mean Squared Error (RMSE):** `0.0791`
* **R² Score:** `0.8888`

These metrics demonstrate strong predictive performance and effective generalization to unseen data.

---

## 📈 Example Output

* **Predicted Emission Factor:** 2.45 kg CO₂e/unit (with margin)
* **Top Influencing Features (from feature importance):**

  * Substance
  * Reliability
  * Technological Correlation
  * Unit

---

## 📌 Use Case

Ideal for:

* Environmental analysts working with supply chain datasets
* Data science learners exploring regression and feature engineering
* Sustainability professionals seeking actionable emission insights
* Researchers studying the relationship between data quality and model accuracy

---

## 🙋‍♀️ Creator

<div align="center">  
Made with 💡 and logic by <b>V. Srinitya Gargeyi</b>  
<br>  
ECE (AIML), GITAM (Deemed to be University)  
</div>

---

## 📚 References

* [Scikit-learn Documentation](https://scikit-learn.org/stable/)
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [Seaborn Documentation](https://seaborn.pydata.org/)
* EPA Supply Chain Emission Factors Dataset (2010–2016)
