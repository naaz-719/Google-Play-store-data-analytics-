# Google-Play-store-data-analytics-
# 📊 ***Google Play Store Data Analytics Dashboard: Category Insights and Performance Trends***

An **Interactive Power BI Dashboard** built for analyzing app performance, installs, ratings, and revenue trends using **Python** and **Power BI**.

Developed by: **Naaz Mulla**
Internship Domain: **Data Analytics** 
Organization: **NullClass** 

---

## 🎯 ***Project Objectives and Executive Summary***

The primary objective is to **transform raw Google Play Store data into meaningful insights** that support data-driven decision-making. This project demonstrates skills in data cleaning, feature engineering, visualization, and business-oriented insight generation.

### **Key Focus Areas:**

* Understanding **category-wise performance** and user engagement. 
* **Comparing free vs. paid app trends** (monetization efficiency). 
* Identifying **high-performing app categories**. 
* Visualizing **global install patterns** and tracking **cumulative and monthly install trends**.

---

## ⚙️ ***Technology Stack & Workflow***

| Component | Tool / Language | Purpose |
| :--- | :--- | :--- |
| **Data Cleaning/Prep** | **Python (Pandas, NumPy)** | Handling missing values, removing duplicates, converting metrics to numeric, and exporting cleaned datasets.  |
| **Sentiment Analysis** | **Python (VADER)**  | [cite_start]Merging review data and applying VADER sentiment analysis.  |
| **Visualization** | **Power BI**  | [cite_start]Interactive dashboard design, complex data modeling, and visualization. |
| **Environment** | **Jupyter Notebook**  | [cite_start]Primary environment for data analysis and transformation. |
| **Version Control** | **GitHub**  | [cite_start]Code hosting and project version control.  |

---

## ✨ ***Key Dashboard Features & Logic***

The Power BI dashboard features **seven interactive sheets** (Sheet 1 is the Overview Dashboard) for detailed analysis.

### **1. Dynamic Time-Constraint Visibility (DAX)**

Key visuals are controlled by a **DAX-based time-constraint system** to optimize report focus during specified active hours, a key demonstration of **real-time analytical filtering** skills. 
* **Logic:** A single measure (`All Tasks - Unified Time Constraint`) is applied as a filter to the main charts, showing them only when the measure returns `1`.
* **Placeholder Message:** When the charts are hidden (measure returns `0`), a placeholder text box is shown using **Conditional Formatting on Transparency**, informing the user of the active viewing schedule.

### **2. Analytical Sheet Breakdown**

| Sheet | Focus | Key Visuals |
| :--- | :--- | :--- |
| **Sheet 2** | Ratings & Reviews Analysis | Grouped Bar, Line charts, and Pie chart.|
| **Sheet 3** | Global Installs Visualization | **Choropleth Map** visualizing global distribution. |
| **Sheet 4** | Free vs Paid App Insights | **Dual-Axis Chart** comparing installs and revenue. |
| **Sheet 5** | Install Growth Trends | Time-series **Line Chart** analyzing monthly growth (Task 4).  |
| **Sheet 7** | Cumulative Installs | **Stacked Area Chart** visualizing growth over time.  |

---

## 💡 ***Key Insights & Findings***

The final report successfully converted raw data into actionable intelligence, revealing these top insights:

* **Engagement:** **FAMILY**, **GAME**, and **SPORTS** categories receive the highest total reviews, indicating strong user engagement and quality perception. 
* **Monetization:** **Paid apps generate significantly higher revenue per app** despite lower installs, proving superior monetization efficiency compared to free apps. 
* **Market Dominance:** **PRODUCTIVITY**, **ENTERTAINMENT**, **FAMILY**, **TOOLS**, and **TRAVEL** categories dominate installs globally.
* **Long-Term Growth:** **TOOLS and PRODUCTIVITY** categories contribute the largest share to cumulative installs, indicating sustained popularity.
* **Stable Demand:** **ENTERTAINMENT and COMMUNICATION** show strong year-to-year install growth, signaling stable long-term demand. 

---

## 📁 ***Repository File Structure***

| File | Description |
| :--- | :--- |
| **`Google Playstore_2.pbix`** | The complete **Power BI Desktop file** with the data model, all DAX measures, and final interactive dashboard. |
| **`Null class Tasks.ipynb`** | The **Python Jupyter Notebook** detailing the entire data cleaning, preprocessing, and sentiment analysis pipeline. |
| **`Play Store Data.csv`** | Core dataset containing app details (Category, Installs, Price, Rating, etc.). |
| **`User Reviews.csv`** | Source data containing translated user reviews for sentiment analysis. |
---

## 🔗 ***Links to Live Content***

* **Live Power BI Dashboard:** [Link to the final dashboard is here-](https://app.powerbi.com/links/EFdUvWOLZg?ctid=880db91c-d2b8-4752-96bb-ec6f76398bf3&pbi\_source=linkShare) 
* **Live Presentation (PPT):** [Link to the live ppt:](https://app.powerbi.com/groups/me/reports/beafb12f-a196-45da-b2ca-d94f915275c5/0a36453118b0643d5a0c?bookmarkGuid=889da549-0eb9-42eb-b5bb-6668eefe8749&bookmarkUsage=1&ctid=880db91c-d2b8-4752-96bb-ec6f76398bf3&portalSessionId=13bcee07-5f7e-48e5-ad99-b8414b5e1a58&fromEntryPoint=export)
