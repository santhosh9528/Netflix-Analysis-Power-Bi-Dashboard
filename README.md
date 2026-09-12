# Netflix Content Analysis – Power BI Dashboard 📺

## 📌 Project Overview

This project presents an interactive **Netflix Content Analysis Dashboard** developed using **Microsoft Power BI**.

The objective of this project is to analyze Netflix Movies and TV Shows and identify meaningful patterns across **content type, genres, countries, ratings, IMDb scores, watch hours, monthly views, and release trends**.

The dashboard transforms raw Netflix content data into an interactive analytical report that makes it easier to understand content distribution and audience engagement.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze the distribution of Movies and TV Shows
- Identify popular genres
- Analyze content across countries
- Understand content rating distribution
- Analyze IMDb scores and votes
- Compare watch hours and monthly views
- Study content release trends over time
- Identify high-performing content
- Analyze audience engagement
- Build an interactive Power BI dashboard

---

## 📂 Dataset

The Netflix dataset contains the following information:

- Content ID
- Title
- Type
- Genre
- Country
- Language
- Release Date
- Date Added
- Rating
- Duration
- Votes
- Watch Hours
- IMDb Score
- Monthly Views

Supporting tables used in the Power BI model include:

- Genres
- Countries
- Date Table

---

## 🛠️ Tools & Technologies

The following tools were used in this project:

- **Microsoft Excel** – Dataset preparation
- **Power Query** – Data cleaning and transformation
- **Microsoft Power BI** – Data modeling and dashboard development
- **DAX** – Measures and calculated metrics
- **Data Modeling** – Table relationships
- **Data Visualization** – Interactive reports and charts

---

## 🧹 Data Cleaning & Preparation

Before creating the dashboard, the Netflix dataset was cleaned and transformed using **Power Query**.

The data preparation process included:

- Checking missing values
- Checking duplicate records
- Correcting data types
- Standardizing text values
- Converting date columns
- Handling missing Rating values
- Handling missing Language values
- Replacing required missing categorical values with `Unknown`
- Preparing analysis-ready data

---

## 🔗 Data Modeling

The Power BI data model contains the main Netflix dataset along with supporting dimension tables.

```text
Genres
   ↓
Netflix_Raw
   ↑
Countries

Date_Table
   ↓
Netflix_Raw
```

Relationships were created between the tables to support interactive filtering and analysis.

---

# 📊 Dashboard Analysis

The dashboard provides analysis across multiple areas of Netflix content.

## 🎬 Content Overview

The Content Overview provides a high-level view of the Netflix library.

Analysis includes:

- Total Content
- Movies
- TV Shows
- Movie vs TV Show Distribution
- Content Type Analysis

---

## 🎭 Genre Analysis

Genre analysis helps identify:

- Most common genres
- Genre-wise content distribution
- Popular content categories
- Content concentration across genres

---

## 🌍 Country Analysis

Country analysis examines how Netflix content is distributed across different countries.

This helps identify countries contributing the largest amount of content to the dataset.

---

## ⭐ Rating Analysis

The dashboard analyzes the distribution of Netflix content across different content ratings.

This helps understand how the content library is distributed among different audience classifications.

---

## 🎞️ IMDb Analysis

IMDb Score and Votes are used to analyze content quality and popularity.

The analysis helps compare titles based on:

- IMDb Score
- Number of Votes
- Content Popularity

---

## 👀 Audience Engagement

Audience engagement is analyzed using:

- Watch Hours
- Monthly Views
- Votes

These metrics help identify content receiving higher levels of audience engagement.

---

## 📈 Content Trend Analysis

Release Date and Date Added are used to analyze Netflix content trends over time.

This helps understand:

- Content release patterns
- Historical content trends
- Changes in the Netflix content library over time

---

# 🖼️ Dashboard Preview

![Netflix Content Analysis Dashboard](Netflix%20Dashboard/Screenshot/Netflix%20Dashboard.jpg)

---

## 📈 Dashboard Features

The Power BI dashboard demonstrates the use of:

- KPI Cards
- Bar Charts
- Column Charts
- Line Charts
- Content Type Analysis
- Genre Analysis
- Country Analysis
- Rating Analysis
- IMDb Analysis
- Audience Engagement Analysis
- Interactive Slicers
- Filters
- Tooltips
- Drill-down
- Power Query
- DAX Measures
- Data Modeling

---

## 🔍 Business / Analytical Questions

The dashboard helps answer questions such as:

- How many Movies and TV Shows are available?
- What is the distribution of Movies vs TV Shows?
- Which genres contain the most content?
- Which countries contribute the most content?
- How is content distributed across ratings?
- Which titles have higher IMDb scores?
- Which content receives the highest watch hours?
- Which titles receive the highest monthly views?
- How has content changed over time?
- Which content appears to have stronger audience engagement?

---

## 💡 Analytical Value

This dashboard provides an interactive way to:

- Understand Netflix content distribution
- Identify popular genres
- Compare Movies and TV Shows
- Analyze country-level content
- Examine IMDb performance
- Monitor audience engagement
- Identify high-performing titles
- Understand historical content trends

---

## 📁 Project Structure

```text
Netflix-Analysis-Power-Bi-Dashboard/
│
├── Netflix Dashboard/
│   │
│   ├── Dataset/
│   │   └── Netflix_Dataset.xlsx
│   │
│   ├── Screenshot/
│   │   └── Netflix Dashboard.jpg
│   │
│   └── Netflix.pbix
│
└── README.md
```

---

## 🚀 Skills Demonstrated

This project demonstrates practical knowledge of:

- Data Cleaning
- Data Transformation
- Power Query
- Data Modeling
- Relationships
- DAX
- KPI Development
- Content Analysis
- Data Visualization
- Dashboard Design
- Interactive Slicers
- Filters
- Business Intelligence
- Analytical Thinking

---

## 🎯 Project Goal

The goal of this project is to demonstrate how **Power BI can transform raw entertainment data into meaningful and interactive analytical insights**.

The dashboard provides a clear view of Netflix content across **Movies, TV Shows, genres, countries, ratings, IMDb scores, watch hours, monthly views, and historical trends**.

---

## 📝 Conclusion

This project demonstrates an end-to-end **Netflix Content Analysis workflow using Power BI**.

By combining **Power Query, data cleaning, data modeling, DAX, and interactive visualizations**, the dashboard transforms raw Netflix data into an easy-to-understand analytical report.

The project demonstrates practical skills in **data preparation, Business Intelligence, dashboard development, and data-driven analysis**.

---

## 👤 Author

**Santhosh Kumar M.**

### Data Analytics Skills

**Excel | SQL | Python | Power BI | Power Query | DAX | Data Visualization | Data Analytics**
