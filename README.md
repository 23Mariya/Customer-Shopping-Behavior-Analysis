# 🛍️ Customer Shopping Behavior Analysis

### End-to-end data analytics project using Python, SQL and Power BI

---

## 📌 Project Overview

This project analyzes **retail customer shopping data** to understand buying patterns, customer segments, loyalty and the factors that drive purchases. It covers the full analytics workflow:

1. **Data preparation & EDA (Python):** import, explore and clean the raw dataset.
2. **Data analysis (SQL):** load the cleaned data into a relational database and answer business questions with SQL queries.
3. **Visualization (Power BI):** build an interactive dashboard that highlights key trends for stakeholders.
4. **Reporting:** summarize findings and recommendations in a report and presentation.

---

## 🎯 Business Objectives

- Understand which customer segments contribute the most to revenue
- Identify purchase drivers such as product category, season, discounts and payment method
- Study customer loyalty and repeat-purchase behavior
- Turn the findings into actionable recommendations for the business

> 📄 See **Business Problem Document.pdf** for the full problem statement.

---

## 🧰 Tech Stack

| Area | Tools |
|------|-------|
| Programming | Python (Pandas, NumPy, Matplotlib / Seaborn) |
| Database | PostgreSQL |
| Visualization | Power BI |
| Environment | Jupyter Notebook |
| Reporting | PDF report, PowerPoint presentation |

---

## 📂 Repository Structure

```
├── Business Problem  Document.pdf          # Business problem statement
├── Customer_Shopping_Behavior_Analysis.ipynb   # Data import, EDA, cleaning, SQL connection
├── customer_shopping_behavior.csv          # Raw dataset
├── customer_behavior_sql_queries.sql       # SQL queries answering business questions
├── customer_behavior_dashboard.pbix        # Power BI dashboard
├── Customer Shopping Behavior Analysis.pdf # Project report
├── Customer-Shopping-Behavior-Analysis.pptx# Presentation deck
├── LICENSE
└── README.md
```

---

## ⚙️ Workflow

### 1️⃣ Python: data preparation and EDA
Open `Customer_Shopping_Behavior_Analysis.ipynb` to:
- Import the dataset
- Explore its structure and summary statistics
- Clean the data (missing values, data types, duplicates)
- Connect to the PostgreSQL database and load the cleaned data

### 2️⃣ SQL: business analysis
- Create a database in PostgreSQL
- Load the cleaned data from the notebook
- Run `customer_behavior_sql_queries.sql` to answer the business questions

### 3️⃣ Power BI: dashboard
- Connect Power BI to the PostgreSQL database
- Open `customer_behavior_dashboard.pbix` to explore the interactive dashboard

### 4️⃣ Report and presentation
- `Customer Shopping Behavior Analysis.pdf`: written report with findings
- `Customer-Shopping-Behavior-Analysis.pptx`: stakeholder presentation

---

## 🚀 How to Run This Project

**Prerequisites:** Python 3.11, Jupyter Notebook, PostgreSQL and Power BI Desktop.

```bash
# 1. Clone the repository
git clone https://github.com/23Mariya/Customer-Shopping-Behavior-Analysis.git
cd Customer-Shopping-Behavior-Analysis

# 2. Install the required libraries
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary jupyter

# 3. Launch the notebook
jupyter notebook Customer_Shopping_Behavior_Analysis.ipynb
```

Then update the database connection details in the notebook, load the data, run the SQL file, and open the `.pbix` file in Power BI Desktop.

---

## 👩‍💻 About Me

Hi, I'm **Mariya Kaunain**, a graduate in **Artificial Intelligence and Machine Learning** from **PESITM, Shimoga**, currently looking for opportunities in data and AI.

**Connect with me**
- 💼 LinkedIn: [linkedin.com/in/mariya-kounain](https://www.linkedin.com/in/mariya-kounain/)
- 🐙 GitHub: [github.com/23Mariya](https://github.com/23Mariya)
- 📧 Email: [mariyakounain644@gmail.com](mailto:mariyakounain644@gmail.com)

---

## 📜 License

This project is licensed under the **MIT License**.

```
MIT License

Copyright (c) 2026 Mariya Kaunain

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

⭐ If you found this project useful, consider giving it a star!