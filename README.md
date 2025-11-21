# Google-Play-store-data-analytics-
# 📊 ***Google Play Store Data Analytics Dashboard: Category Insights and Performance Trends***

[cite_start]An **Interactive Power BI Dashboard** built for analyzing app performance, installs, ratings, and revenue trends using **Python** and **Power BI**. [cite: 1, 3]

[cite_start]Developed by: **Naaz Mulla** [cite: 4]
[cite_start]Internship Domain: **Data Analytics** [cite: 5]
[cite_start]Organization: **NullClass** [cite: 6]
[cite_start]Duration: **[21 Sept. 2025 - 21 Nov. 2025]** [cite: 7]
[cite_start]Submission Date: **[21/11/2025]** [cite: 8]

---

## 🎯 ***Project Objectives and Executive Summary***

[cite_start]The primary objective is to **transform raw Google Play Store data into meaningful insights** that support data-driven decision-making. [cite: 15] [cite_start]This project demonstrates skills in data cleaning, feature engineering, visualization, and business-oriented insight generation. [cite: 13]

### **Key Focus Areas:**

* [cite_start]Understanding **category-wise performance** and user engagement. [cite: 16]
* [cite_start]**Comparing free vs. paid app trends** (monetization efficiency). [cite: 17, 64]
* [cite_start]Identifying **high-performing app categories**. [cite: 18]
* [cite_start]Visualizing **global install patterns** and tracking **cumulative and monthly install trends**. [cite: 19, 21]

---

## ⚙️ ***Technology Stack & Workflow***

| Component | Tool / Language | Purpose |
| :--- | :--- | :--- |
| **Data Cleaning/Prep** | [cite_start]**Python (Pandas, NumPy)** [cite: 24, 44] | [cite_start]Handling missing values, removing duplicates, converting metrics to numeric, and exporting cleaned datasets. [cite: 45, 46, 51] |
| **Sentiment Analysis** | [cite_start]**Python (VADER)** [cite: 24] | [cite_start]Merging review data and applying VADER sentiment analysis. [cite: 49] |
| **Visualization** | [cite_start]**Power BI** [cite: 25] | [cite_start]Interactive dashboard design, complex data modeling, and visualization. [cite: 32] |
| **Environment** | [cite_start]**Jupyter Notebook** [cite: 28] | [cite_start]Primary environment for data analysis and transformation. [cite: 35] |
| **Version Control** | [cite_start]**GitHub** [cite: 27] | [cite_start]Code hosting and project version control. [cite: 34] |

---

## ✨ ***Key Dashboard Features & Logic***

The Power BI dashboard features **seven interactive sheets** (Sheet 1 is the Overview Dashboard) for detailed analysis.

### **1. Dynamic Time-Constraint Visibility (DAX)**

[cite_start]Key visuals are controlled by a **DAX-based time-constraint system** to optimize report focus during specified active hours, a key demonstration of **real-time analytical filtering** skills. [cite: 75]

* **Logic:** A single measure (`All Tasks - Unified Time Constraint`) is applied as a filter to the main charts, showing them only when the measure returns `1`.
* **Placeholder Message:** When the charts are hidden (measure returns `0`), a placeholder text box is shown using **Conditional Formatting on Transparency**, informing the user of the active viewing schedule.

### **2. Analytical Sheet Breakdown**

| Sheet | Focus | Key Visuals |
| :--- | :--- | :--- |
| **Sheet 2** | Ratings & Reviews Analysis | [cite_start]Grouped Bar, Line charts, and Pie chart. [cite: 55] |
| **Sheet 3** | Global Installs Visualization | [cite_start]**Choropleth Map** visualizing global distribution. [cite: 56] |
| **Sheet 4** | Free vs Paid App Insights | [cite_start]**Dual-Axis Chart** comparing installs and revenue. [cite: 57] |
| **Sheet 5** | Install Growth Trends | [cite_start]Time-series **Line Chart** analyzing monthly growth (Task 4). [cite: 58] |
| **Sheet 7** | Cumulative Installs | [cite_start]**Stacked Area Chart** visualizing growth over time. [cite: 60] |

---

## 💡 ***Key Insights & Findings***

[cite_start]The final report successfully converted raw data into actionable intelligence, revealing these top insights: [cite: 78]

* [cite_start]**Engagement:** **FAMILY**, **GAME**, and **SPORTS** categories receive the highest total reviews, indicating strong user engagement and quality perception. [cite: 62]
* [cite_start]**Monetization:** **Paid apps generate significantly higher revenue per app** despite lower installs, proving superior monetization efficiency compared to free apps. [cite: 64]
* [cite_start]**Market Dominance:** **PRODUCTIVITY**, **ENTERTAINMENT**, **FAMILY**, **TOOLS**, and **TRAVEL** categories dominate installs globally. [cite: 63]
* [cite_start]**Long-Term Growth:** **TOOLS and PRODUCTIVITY** categories contribute the largest share to cumulative installs, indicating sustained popularity. [cite: 67]
* [cite_start]**Stable Demand:** **ENTERTAINMENT and COMMUNICATION** show strong year-to-year install growth, signaling stable long-term demand. [cite: 65]

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

* [cite_start]**Live Power BI Dashboard:** [Link to the final dashboard is here-](https://app.powerbi.com/links/EFdUvWOLZg?ctid=880db91c-d2b8-4752-96bb-ec6f76398bf3&pbi\_source=linkShare) [cite: 79]
* [cite_start]**Live Presentation (PPT):** [Link to the live ppt:](https://app.powerbi.com/groups/me/reports/beafb12f-a196-45da-b2ca-d94f915275c5/0a36453118b0643d5a0c?bookmarkGuid=889da549-0eb9-42eb-b5bb-6668eefe8749&bookmarkUsage=1&ctid=880db91c-d2b8-4752-96bb-ec6f76398bf3&portalSessionId=13bcee07-5f7e-48e5-ad99-b8414b5e1a58&fromEntryPoint=export) [cite: 80, 81, 82]
