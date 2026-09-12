# Netflix-Analysis-Power-Bi-Dashboard
Interactive Netflix Content Analysis Dashboard built with Power BI to analyze movies, TV shows, genres, countries, ratings, IMDb scores, watch hours, and content trends.
# Netflix Content Analysis Dashboard 📺

## Project Overview

This project presents an interactive **Netflix Content Analysis Dashboard** developed using **Microsoft Power BI**.

The objective of the project is to analyze Netflix movies and TV shows and understand content distribution, genres, countries, ratings, IMDb scores, watch hours, views, and release trends.

The dashboard transforms raw Netflix content data into meaningful visual insights that make it easier to understand the platform's content library and audience engagement.

---

## Project Objective

The main objectives of this project are to:

- Analyze the distribution of Movies and TV Shows
- Identify popular genres
- Analyze content by country
- Understand content rating distribution
- Analyze IMDb scores
- Compare watch hours and monthly views
- Study content release trends over time
- Identify high-performing content
- Build an interactive Power BI dashboard

---

## Dataset

The dataset contains Netflix content information including:

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

The project also uses supporting tables for:

- Genres
- Countries
- Date Table

---

## Tools Used

- **Microsoft Excel** – Dataset preparation
- **Power Query** – Data cleaning and transformation
- **Power BI** – Data modeling, DAX, analysis, and visualization
- **DAX** – Measures and calculated metrics

---

## Data Cleaning

Before creating the dashboard, the dataset was cleaned and transformed using Power Query.

The cleaning process included:

- Checking missing values
- Checking duplicate records
- Correcting data types
- Standardizing text values
- Converting date columns
- Handling missing Rating values
- Handling missing Language values
- Replacing required missing categorical values with `Unknown`
- Preparing the dataset for analysis

---

## Data Modeling

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

Relationships were created to support filtering and interactive analysis.

---

## Dashboard Analysis

The dashboard provides analysis across several areas.

### Content Overview

Analyzes:

- Total Content
- Movies
- TV Shows
- Content Type Distribution

### Genre Analysis

Helps identify:

- Most common genres
- Genre-wise content distribution
- Popular content categories

### Country Analysis

Analyzes Netflix content across different countries to identify locations contributing the most content.

### Rating Analysis

Shows the distribution of content based on Netflix ratings.

### IMDb Analysis

Uses IMDb Score and Votes to understand content quality and popularity.

### Audience Engagement

Audience engagement is analyzed using:

- Watch Hours
- Monthly Views
- Votes

### Content Trend Analysis

Release Date and Date Added are used to understand how Netflix content changes over time.

---

## Dashboard Features

The Power BI dashboard includes:

- KPI Cards
- Bar Charts
- Column Charts
- Line Charts
- Content Type Analysis
- Genre Analysis
- Country Analysis
- Rating Analysis
- Interactive Slicers
- Filters
- Tooltips
- Drill-down functionality

---

## Key Skills Demonstrated

This project demonstrates practical knowledge of:

- Data Cleaning
- Power Query
- Data Transformation
- Data Modeling
- Relationships
- DAX
- KPI Development
- Data Visualization
- Dashboard Design
- Filtering and Slicers
- Business Intelligence
- Analytical Thinking

---

## Project Structure

```text
Netflix-Content-Analysis/
│
├── Dataset/
│   └── Netflix_Dataset.xlsx
│
├── PowerBI/
│   └── Netflix.pbix
│
├── Screenshots/
│   └── Netflix_Dashboard.png
│
└── README.md
```

---

## Dashboard

The Power BI dashboard provides an interactive way to explore Netflix content and understand patterns across content type, genres, countries, ratings, IMDb scores, watch hours, and monthly views.

> Add your dashboard screenshot here after uploading it to the `Screenshots` folder.

```markdown
![Netflix Dashboard](Screenshots/Netflix_Dashboard.png)
```

---

## Conclusion

This project demonstrates how **Power BI can transform raw entertainment data into an interactive analytical dashboard**.

The analysis helps understand Netflix's content distribution, audience engagement, content ratings, genres, countries, and historical trends through clear and interactive visualizations.

---

## Author

**Santhosh Kumar M.**

### Data Analytics Skills

**Excel | SQL | Python | Power BI | Power Query | DAX | Data Visualization**

---

⭐ If you found this project useful, feel free to explore the dashboard and other data analytics projects in my GitHub profile.
