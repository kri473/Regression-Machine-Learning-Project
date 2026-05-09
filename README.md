# Regression-Machine-Learning-Project
# 🚗 Used Cars Price Prediction - Regression Machine Learning Project

## 📌 Project Overview

This project focuses on predicting the selling price of used cars using different Machine Learning Regression algorithms. The notebook includes complete Exploratory Data Analysis (EDA), data preprocessing, feature engineering, model training, and performance evaluation.

The main goal of this project is to compare multiple regression models and identify the best-performing algorithm for used car price prediction.

---

# 📂 Dataset Information

The dataset used in this project contains information about used cars such as:

* Car Year
* Kilometers Driven
* Fuel Type
* Transmission
* Owner Type
* Mileage
* Engine Capacity
* Power
* Seats
* Selling Price

Dataset File:
`used_cars_data.csv`

---

# 🛠️ Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 📊 Exploratory Data Analysis (EDA)

The project includes:

## ✅ Univariate Analysis

* Histograms
* KDE Plots
* Count Plots

## ✅ Bivariate Analysis

* Scatter Plots
* Box Plots

## ✅ Multivariate Analysis

* Correlation Matrix
* Pair Plots

---

# ⚙️ Data Preprocessing

The following preprocessing steps were performed:

* Handling Missing Values
* Outlier Detection using Boxplots
* Outlier Treatment using IQR Method
* Feature Scaling
* One-Hot Encoding for Categorical Features
* Train-Test Split

---

# 🤖 Machine Learning Models Used

The following regression algorithms were trained and evaluated:

1. Linear Regression
2. Support Vector Regressor (SVR)
3. K-Nearest Neighbors Regressor (KNN)
4. Bagging Regressor
5. AdaBoost Regressor
6. Random Forest Regressor
7. Stacking Regressor

---

# 📈 Model Performance

| Model                   | MSE  | R² Score |
| ----------------------- | ---- | -------- |
| Linear Regression       | 2.61 | 0.55     |
| SVR                     | 1.80 | 0.69     |
| KNN Regressor           | 2.19 | 0.63     |
| Bagging Regressor       | 1.95 | 0.67     |
| AdaBoost Regressor      | 2.91 | 0.50     |
| Random Forest Regressor | 1.86 | 0.68     |
| Stacking Regressor      | 1.69 | 0.71     |

### 🏆 Best Performing Model

The **Stacking Regressor** achieved the best performance with:

* **Lowest MSE:** 1.69
* **Highest R² Score:** 0.71

---

# 📌 Key Insights

* Newer cars generally have higher selling prices.
* Cars with fewer kilometers driven tend to retain better value.
* Engine power and horsepower strongly influence car prices.
* Automatic transmission cars are usually more expensive than manual cars.
* Diesel cars often have higher resale prices compared to petrol cars.

---

# 🚀 Project Workflow

```text
Data Collection
       ↓
Data Cleaning
       ↓
EDA & Visualization
       ↓
Feature Engineering
       ↓
Data Preprocessing
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Performance Comparison
```

---

# 📷 Visualizations Included

* Boxplots
* Histograms
* KDE Plots
* Scatter Plots
* Correlation Heatmap
* Pair Plot
* Model Comparison Graphs

---

# ▶️ How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

## 2️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 3️⃣ Run the Notebook

Open Jupyter Notebook and run:

```bash
Regression_Machine_Learning_project.ipynb
```

---

# 📁 Project Structure

```text
📦 Used-Car-Price-Prediction
 ┣ 📜 Regression_Machine_Learning_project.ipynb
 ┣ 📜 used_cars_data.csv
 ┗ 📜 README.md
```

---

# 🎯 Conclusion

This project demonstrates how different regression algorithms can be applied to predict used car prices effectively. After comparing multiple models, the Stacking Regressor delivered the best performance among all tested algorithms.

The project also highlights the importance of:

* Data preprocessing
* Feature engineering
* Proper model evaluation
* Comparative analysis of machine learning models

---

# 👨‍💻 Author

**Krishna Kumar**

* Aspiring Data Scientist
* Interested in Machine Learning, Data Analytics, and NLP

---

# ⭐ If You Like This Project

Give this repository a ⭐ on GitHub and share your feedback!
