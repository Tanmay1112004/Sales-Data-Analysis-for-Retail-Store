# 📊 Sales Data Analysis for Retail Store

### Turning Retail Data into Actionable Business Insights 🛒

> **Data-driven decisions start with understanding your sales.**

This project performs a comprehensive **statistical and exploratory analysis** on retail sales data to uncover patterns, validate assumptions, and support smarter business decisions in inventory and marketing.

---

## Demo Images

![demo](https://github.com/Tanmay1112004/Sales-Data-Analysis-for-Retail-Store/blob/main/Sales%20Data%20Analysis%20For%20Retail%20Store%20Using%20Statistical%20Approch/app%20screenshots/Screenshot%202025-07-31%20102059.png)

![demo](https://github.com/Tanmay1112004/Sales-Data-Analysis-for-Retail-Store/blob/main/Sales%20Data%20Analysis%20For%20Retail%20Store%20Using%20Statistical%20Approch/app%20screenshots/Screenshot%202025-07-31%20102143.png)

![demo](https://github.com/Tanmay1112004/Sales-Data-Analysis-for-Retail-Store/blob/main/Sales%20Data%20Analysis%20For%20Retail%20Store%20Using%20Statistical%20Approch/app%20screenshots/Screenshot%202025-07-31%20102243.png)

![demo](https://github.com/Tanmay1112004/Sales-Data-Analysis-for-Retail-Store/blob/main/Sales%20Data%20Analysis%20For%20Retail%20Store%20Using%20Statistical%20Approch/app%20screenshots/Screenshot%202025-07-31%20102323.png)
![demo](https://github.com/Tanmay1112004/Sales-Data-Analysis-for-Retail-Store/blob/main/Sales%20Data%20Analysis%20For%20Retail%20Store%20Using%20Statistical%20Approch/app%20screenshots/Screenshot%202025-07-31%20102059.png)

![demo](https://github.com/Tanmay1112004/Sales-Data-Analysis-for-Retail-Store/blob/main/Sales%20Data%20Analysis%20For%20Retail%20Store%20Using%20Statistical%20Approch/app%20screenshots/Screenshot%202025-07-31%20102143.png)

![demo](https://github.com/Tanmay1112004/Sales-Data-Analysis-for-Retail-Store/blob/main/Sales%20Data%20Analysis%20For%20Retail%20Store%20Using%20Statistical%20Approch/app%20screenshots/Screenshot%202025-07-31%20102243.png)

![demo](https://github.com/Tanmay1112004/Sales-Data-Analysis-for-Retail-Store/blob/main/Sales%20Data%20Analysis%20For%20Retail%20Store%20Using%20Statistical%20Approch/app%20screenshots/Screenshot%202025-07-31%20102323.png)

----

## 🚀 Project Overview

In a competitive retail environment, guessing is expensive — data is leverage.

This project analyzes sales performance across multiple product categories using **descriptive statistics, hypothesis testing, and visual analytics**.

🎯 **Objective:**
Transform raw sales data into **clear insights for decision-making**

---

## 📋 Business Use Case

Retail managers need to answer:

* Which categories perform best?
* Is average sales meeting expectations?
* How consistent are sales across products?

➡️ This project provides statistically grounded answers.

---

## 🗂️ Dataset Overview

A synthetic dataset simulating real retail scenarios:

| Feature      | Description                                 |
| ------------ | ------------------------------------------- |
| product_id   | Unique identifier                           |
| product_name | Product label                               |
| category     | Electronics, Clothing, Home, Sports         |
| units_sold   | Sales volume (Poisson distribution, λ = 20) |
| sale_date    | Sales timeline (Jan 1–20, 2023)             |

📊 **Scale:**

* 20 products
* 4 categories

---

## 🔍 Analysis Breakdown

### 📈 Descriptive Statistics

Understanding the core behavior of sales:

* Mean, Median, Mode
* Variance & Standard Deviation
* Category-wise aggregation

➡️ Helps identify central trends and variability

---

### 📉 Inferential Statistics

Validating assumptions with statistical rigor:

* **Confidence Intervals** (95% & 99%)
* **One-sample T-test** against expected mean (20 units)

➡️ Determines whether observed sales differ significantly from expectations

---

### 📊 Data Visualization

Visual storytelling for faster insights:

* 📈 **Histogram** → Sales distribution
* 📊 **Boxplot** → Outliers & spread by category
* 📉 **Bar Chart** → Category-wise performance

➡️ Converts numbers into intuitive insights

---

## 🎯 Key Insights

📌 Mean sales (~18.8) slightly below expected (20)
📌 P-value > 0.05 → No significant difference from target
📌 “Home” category shows strongest performance
📌 Sales variability exists across categories

➡️ Insight: System is stable, but category optimization can boost performance

---

## 🛠️ Tech Stack

* **Python**
* **Pandas & NumPy** → Data manipulation
* **Matplotlib & Seaborn** → Visualization
* **SciPy** → Statistical testing

---

## ⚙️ Installation & Setup

### 🔹 Clone Repository

```bash
git clone https://github.com/<your-username>/Retail-Sales-Analysis.git
cd Retail-Sales-Analysis
```

---

### 🔹 Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 🔹 Run Analysis

```bash
python sales_data_analysis.py
```

---

## 📂 Project Structure

```text
Retail-Sales-Analysis/
│
├── sales_data_analysis.py   # Core analysis script
├── sales_data.csv           # Dataset
├── requirements.txt         # Dependencies
└── README.md                # Documentation
```

---

## 🧪 Sample Output

```
Mean Units Sold: 18.80  
Median Units Sold: 18.50  
Mode Units Sold: 17  

Confidence Interval (95%): (17.25, 20.35)  

T-test:
T-statistic: -1.63  
P-value: 0.12  
→ Fail to reject null hypothesis
```

---

## 💼 Why This Project Matters

This project demonstrates:

🔥 Strong foundation in statistics
🔥 Real-world data analysis thinking
🔥 Ability to translate data → business insights
🔥 Visualization for stakeholder communication
🔥 End-to-end analytical workflow

➡️ Exactly what recruiters expect in a Data Analyst role

---

## 🔮 Future Improvements

Planned enhancements:

🔹 Dashboard (Streamlit / Power BI)
🔹 Real-world dataset integration
🔹 Time-series forecasting
🔹 Advanced statistical modeling
🔹 ML-based sales prediction

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch
3. Submit a pull request

---

## 📜 License

MIT License — free to use and modify.

---

## 👨‍💻 Author

**Tanmay Kshirsagar**

💻 GitHub: [https://github.com/Tanmay1112004](https://github.com/Tanmay1112004)
💼 LinkedIn: [https://linkedin.com/in/tanmay-kshirsagar](https://linkedin.com/in/tanmay-kshirsagar)

---

## ⭐ Support

If this project helped you:

➡️ Star ⭐ the repo
➡️ Share feedback
➡️ Connect with me

---

## 💬 Final Thought

> “Without data, you’re just another person with an opinion.”

---
