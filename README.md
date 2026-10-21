# 📺 OTT Subscriber Churn & Retention Analysis

<p align="center">
  <strong>Turning Subscriber Data into Retention Insights</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL%20Server-Business%20Queries-CC2927?logo=microsoftsqlserver" alt="SQL Server"/>
  <img src="https://img.shields.io/badge/Power%20BI-Dashboards-F2C811?logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Excel-Data%20Analysis-217346?logo=microsoftexcel&logoColor=white" alt="Excel"/>
</p>

## 📌 Project Overview

Why do OTT subscribers cancel their subscriptions, and which customer segments should a streaming business investigate to improve retention?

This project explores subscriber churn patterns using Python, SQL Server, Excel, and Power BI. It combines exploratory data analysis, business-focused SQL queries, and interactive dashboards to understand how churn varies across subscription plans, payment methods, viewing engagement, and device segments.

The goal is to go beyond reporting numbers and translate analytical findings into practical business questions and retention opportunities.

**Important:** This is a Netflix-themed OTT case study using sample data. It is not based on confidential Netflix or ZEE5 data and is not an official analysis for either company.

## 🎯 Business Questions

- What percentage of subscribers have churned?
- Does churn differ between Basic and Premium subscribers?
- How does churn vary across payment methods?
- What patterns appear in subscriber viewing engagement?
- Which device or subscription segments show higher churn?
- What estimated monthly subscription-fee value is associated with churned subscribers?
- What further analysis could help a streaming business improve retention?

## 🛠️ Tools Used

| Tool | How it was used |
|---|---|
| Python | Data preparation and exploratory analysis |
| Pandas & NumPy | Data manipulation and calculations |
| SQL Server | Business queries, aggregations, and segmentation |
| Excel | Supporting analysis and data review |
| Power BI | Dashboard design and visual reporting |

## 📊 Dashboard Gallery

The project contains three dashboard pages, each designed to answer a different set of business questions.

### 1. Executive Overview

*Focus: What does the overall subscriber and churn picture look like?*

<p align="center">
  <img src="./Dashboards/Page1-Executive-Overview.png" alt="Executive Overview Dashboard" width="900">
</p>

### 2. Subscriber Retention Analysis

*Focus: How does churn differ across subscriber segments, payment methods, and engagement patterns?*

<p align="center">
  <img src="./Dashboards/Page2-Retention-Engagement.png" alt="Subscriber Retention Dashboard" width="900">
</p>

### 3. Business Insights & Recommendations

*Focus: What should the business investigate next based on the observed patterns?*

<p align="center">
  <img src="./Dashboards/Page3-Customer-Segments.png" alt="Customer Segments and Retention Priorities Dashboard" width="900">
</p>

## 🔍 Key Findings

The analysis identified these patterns in the current dataset:

| Metric | Finding |
|---|---:|
| Subscriber records analyzed | 5,000 |
| Overall churn rate | 50.3% |
| Basic plan churn rate | 61.83% |
| Premium plan churn rate | 43.71% |

**What these results suggest:**

- The Basic plan has a higher observed churn rate than the Premium plan.
- The difference between subscription segments warrants further investigation.
- Payment methods and engagement measures provide additional dimensions for exploring subscriber behavior.

These are descriptive findings from the dataset. They do not prove that subscription plans or other observed characteristics cause churn.

## 💡 Business Recommendations

Based on the observed patterns, a streaming business could:

1. **Investigate Basic plan churn:** Explore pricing, perceived value, content preferences, and renewal behavior.
2. **Study subscriber engagement:** Determine whether lower viewing activity is associated with cancellations using suitable time-based data.
3. **Review payment behavior:** Examine failed payments, renewal issues, and differences across payment methods.
4. **Test retention initiatives:** Evaluate targeted content recommendations, renewal reminders, or re-engagement campaigns through controlled experiments.
5. **Monitor segment-level churn:** Track churn over time rather than relying only on an overall rate.

These are recommendations for further investigation and testing, not guaranteed solutions.

## 🔄 Project Workflow

```text
Subscriber Dataset
        ↓
Data Inspection & Preparation
        ↓
Python Exploratory Analysis
        ↓
SQL Business Analysis
        ↓
Power BI Dashboards
        ↓
Findings & Retention Recommendations
```

## 📁 Repository Structure

```text
OTT-Subscriber-Churn-Retention-Analysis/
│
├── Dashboards/       # Dashboard screenshots
├── dataset/          # OTT subscriber dataset
├── python-analysis/  # Python analysis notebook
├── sql-analysis/     # SQL queries and analysis results
└── README.md         # Project documentation
```

## ⚠️ Data Quality & Limitations

- Ten records were identified with viewing times exceeding 24 hours per day. These observations require validation before interpreting viewing behavior.
- The dataset is a sample and should not be treated as representative of all OTT subscribers.
- A single snapshot may not be sufficient to establish long-term retention or cohort behavior.
- The observed relationships do not establish causation.
- Estimated monthly-fee exposure is not necessarily equal to actual revenue lost.

These limitations matter because good business decisions depend on understanding both what the data shows and what it cannot establish.

## 🚀 How to Explore the Project

1. Open the dashboard screenshots to review the main findings.
2. Explore the Python notebook to understand the data preparation and exploratory analysis.
3. Review the SQL queries and results to see how the business questions were investigated.
4. Compare the findings with the recommendations and limitations documented here.

### Python Environment

Install the main analysis libraries if needed:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Open the Python notebook in Jupyter Notebook or JupyterLab and execute the cells in order. Confirm the dataset path in the notebook before running it.

SQL queries are provided separately in the `sql-analysis/` folder.

## 👩‍💻 About the Author

**Neha Shinge**

Aspiring Data Analyst interested in using SQL, Python, and business intelligence tools to solve practical business problems.

- [GitHub Profile](https://github.com/Neha664)
- [Project Repository](https://github.com/Neha664/ott-subscriber-churn-retention-analysis)

---

*This project demonstrates an end-to-end analytical workflow: investigating a business problem, analyzing subscriber data, presenting findings visually, and identifying evidence-based next steps.*
