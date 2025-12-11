
---

# Customer Segmentation Dashboard - Power BI

This project showcases a **Customer Segmentation Dashboard** created using **Power BI**. The dashboard is designed to provide insights into customer demographics and spending behavior using a simplified dataset.

## 📊 Dashboard Overview

The dashboard visualizes and summarizes customer data including:

* **Total Spending Score** (1–100 scale)
* **Annual Income** (in thousands)
* **Customer Count**
* **Gender-based analysis** of spending and income
* **Age and Income Distribution**

## 🧾 Key Insights

* **Total Customers**: 200
* **Total Annual Income**: 12,000 k\$
* **Total Spending Score**: 10,000
* **Gender Comparison**:

  * Female customers have a higher combined spending score than male customers.
  * Female customers also contribute slightly more to total annual income.

## 📌 Visuals Included

* Donut chart: Sum of Age vs. Sum of Income
* Card KPIs: Customer count, Spending Score total, Income total
* Gauge chart: Customer count
* Bar chart: Spending Score by Gender
* Pie chart: Annual Income by Gender
* Area chart: Spending Score trend by Gender

## 📂 Dataset Used

A clean, structured dataset with the following fields:

* `CustomerID`
* `Gender`
* `Age`
* `Annual Income (k$)`
* `Spending Score (1-100)`

> Note: The dataset used is based on the **Mall Customers dataset**, a commonly used dataset for segmentation and clustering projects. It is clean and ready for analytics or ML workflows.

## 💻 Tools Used

* **Power BI Desktop**
* Data cleaning and visualization techniques
* DAX measures for aggregations

## 🚀 Future Improvements

* Add clustering (K-Means) using Python visual
* Age group segmentation
* Interactive filters for city/location (if available)
* Time series or change tracking (with longitudinal data)


