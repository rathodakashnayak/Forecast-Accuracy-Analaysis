# 📊 Forecast Accuracy Assessment – Statistical vs Machine Learning Approach

## 🚀 Project Overview

This project analyzes and improves forecast accuracy for a **medical devices supply chain dataset**.
The goal is to compare **Statistical Forecast (Stat FC)** and **Consensus Forecast (Cons FC)** against actual demand and demonstrate how **data-driven methods** can significantly enhance forecasting performance.

---

## 🎯 Objectives

* Evaluate forecast accuracy using robust metrics
* Identify key drivers of forecast errors
* Perform segmentation analysis (Category, Region, Promotion, Stockout)
* Improve Statistical Forecast using data-driven techniques
* Demonstrate measurable business impact

---

## 🧠 Key Concepts Used

* Forecast Accuracy Metrics (WAPE, MAE, Bias)
* Exploratory Data Analysis (EDA)
* Segmentation Analysis
* Feature Engineering
* Machine Learning (Linear Regression)

---

## 📂 Dataset Description

The dataset includes:

* 📦 Product hierarchy (Category, Region)
* 📈 Actual Sales
* 🤖 ERP Statistical Forecast (Stat FC)
* 🧑‍💼 Consensus Forecast (Cons FC)
* 🎯 Promotion Indicators
* ⚠️ Stockout Information

---

## 📊 Methodology

### 🔹 1. Data Preparation

* Cleaned missing and inconsistent values
* Converted categorical variables to numeric
* Created error and absolute error features

---

### 🔹 2. Exploratory Data Analysis (EDA)

* Demand distribution analysis
* Forecast vs Actual comparison
* Promotion & stockout impact analysis
* Correlation analysis

---

### 🔹 3. Forecast Accuracy Metrics

* **WAPE (Primary Metric)**
* MAE (Mean Absolute Error)
* Bias (Over/Under Forecast detection)

---

### 🔹 4. Segmentation Analysis

Performance evaluated across:

* Category
* Region
* Promotion vs Non-Promotion
* Stockout vs In-Stock

---

### 🔹 5. Forecast Improvement Techniques

* Bias Correction
* Promotion Uplift Adjustment
* 🤖 Machine Learning Model (Linear Regression)

---

## 📈 Results

| Model                | WAPE     |
| -------------------- | -------- |
| Statistical Forecast | 0.64     |
| Bias Adjusted        | 0.61     |
| Promotion Adjusted   | 0.64     |
| 🤖 ML Forecast       | **0.39** |

👉 **~38% improvement achieved using Machine Learning**

---

## 🔍 Key Insights

* Statistical Forecast fails to capture real-world demand drivers
* Promotions significantly impact demand but are not modeled properly
* Stockouts distort actual demand and forecast accuracy
* Forecast performance varies across categories and regions
* Machine Learning effectively captures complex relationships

---

## 💡 Business Impact

* 📉 Reduced forecast error
* 📦 Better inventory planning
* 🚚 Improved supply chain efficiency
* 💰 Reduced costs due to overstock and stockouts

---

## 🔧 Recommendations

* Integrate external factors (promotion, stock availability) into forecasting
* Use ML-based models alongside statistical methods
* Apply segmentation-based forecasting strategies
* Incorporate time-based features (seasonality, lag demand)

---

## 🏆 Conclusion

Statistical forecasting alone is insufficient for accurate demand prediction.
A hybrid approach combining **statistical methods + machine learning** significantly improves forecast accuracy and business outcomes.

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
* Excel (Pivot Tables, Conditional Formatting)
* Jupyter Notebook

---

## 📌 How to Run

```bash
# Clone repository
git clone <your-repo-link>

# Open notebook
jupyter notebook
```

---

## 👤 Author

**Rathod Akash Nayak**
🎓 B.Sc Statistics & Data Science
💻 Aspiring Data Analyst | ML Enthusiast

---

## ⭐ If you found this useful

Give a ⭐ to the repository and feel free to connect!
