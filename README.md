# Customer-Complaint-Analysis

An end-to-end data analytics project that transforms raw consumer complaint data into actionable insights and a live, interactive web dashboard.

## 🚀 Project Overview
This project demonstrates the full lifecycle of a data analytics pipeline—from raw data ingestion to deployment of a professional web-based dashboard. The project focuses on understanding consumer grievances, identifying trends in product issues, and analyzing company response performance.

## 🛠️ Data Pipeline & Notebooks
The workflow follows a structured approach to data transformation:
1.  **Data Ingestion & Understanding:** Sourced raw consumer complaint records from the [Consumer Complaint Database (Data.gov)](https://catalog.data.gov/dataset/consumer-complaint-database) (originally from Kaggle/CFPB), and performed initial profiling and validation using Google Colab.
    *   🔗 **[Data Ingestion & Understanding Notebook](https://colab.research.google.com/drive/1G-DjgOLOBm4d6PNQdYnjN5PJFZFpF6f9?usp=sharing)**
2.  **Exploratory Data Analysis (EDA):** Conducted deep-dive analysis using Python and Pandas in Google Colab to uncover key patterns, complaint volumes, and correlations.
    *   🔗 **[EDA Notebook](https://colab.research.google.com/drive/1q_oy_xZWCDf9uN0zMLQc86_n4NS3QnfQ?usp=sharing)**
3.  **Data Warehousing (BigQuery):** Exported cleaned datasets to Google BigQuery, where custom SQL queries were authored to extract critical business metrics such as response timeliness and dispute rates.
4.  **Dashboard Deployment:** Utilized **Lovable AI** to build and host a fully responsive, modern dashboard to visualize the data.

## 📊 Live Dashboard
You can interact with the live dashboard here:
👉 **[https://compaint-view.lovable.app](https://compaint-view.lovable.app)**

## 🛠️ Tech Stack
*   **Data Processing & Notebooks:** Python, Pandas, Google Colab
*   **Data Warehousing:** Google BigQuery
*   **Analytics & Querying:** SQL
*   **Frontend & Visualization:** Lovable AI, React, Tailwind CSS, Recharts

## 🔑 Key SQL Insights
The project utilizes BigQuery to answer critical questions such as:
*   Percentage of complaints with timely vs. non-timely responses.
*   Top issue types reported under specific product categories (e.g., Credit Reporting).
*   Company public response trends regarding disputes and corrections.

---
*Created by Shambhavi Srivastava | Data Science Undergraduate*
