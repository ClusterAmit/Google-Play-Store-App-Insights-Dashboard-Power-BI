# 📱 Google Play Store – App Insights Dashboard | Power BI

## 📌 Project Overview

This project focuses on analysing Google Play Store application data using **Microsoft Power BI** to understand app performance, user ratings, market trends, popularity, and user engagement.

The interactive dashboard provides insights into app categories, installation trends, free vs. paid applications, rating distribution, content ratings, and review patterns.

The objective is to transform raw application data into meaningful business insights that can help understand market preferences and app performance.

## 🎯 Business Objectives

- Analyse app distribution across different categories.
- Identify categories generating the highest number of installs.
- Compare free and paid applications.
- Understand user rating distribution and satisfaction.
- Identify the most popular applications based on installs.
- Compare average reviews between free and paid apps.
- Explore the relationship between app installs and ratings.
- Analyse application distribution by content rating.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Dataset preparation and initial inspection |
| Power Query | Data cleaning and transformation |
| Power BI | Interactive dashboard development |
| DAX | KPI calculations and analytical measures |
| Data Visualization | Business insights and performance analysis |

## 📊 Dashboard Overview

The dashboard provides a consolidated view of Google Play Store app performance through KPI cards, interactive filters, and analytical charts.

### 1. Key Performance Indicators (KPIs)

The dashboard includes the following KPIs:

- **Unique Apps:** Total distinct applications.
- **Average Rating:** Overall average app rating.
- **Total Installs:** Combined recorded installations.
- **Total Reviews:** Combined review count.
- **Free Apps:** Number of free applications.
- **Paid Apps:** Number of paid applications.

### 2. Visualizations & Analysis

| Visualization | Business Question |
|---|---|
| Installs by Category | Which categories generated the most installs? |
| Apps by Type | What is the distribution of free and paid apps? |
| Top 5 Apps | Which applications have the highest installs? |
| Average Reviews by Type | How does user engagement differ between free and paid apps? |
| Rating Distribution | How are applications distributed across rating groups? |
| Content Rating | Which content rating is most common? |
| Installs vs Popularity | How do app installs relate to ratings and popularity? |

### 3. Interactive Filters

The dashboard includes the following slicers:

- Category
- Type (Free/Paid)
- Content Rating
- Rating Group
- Year

Users can apply multiple filters to explore specific segments of the app market.

## 🔍 Key Insights & Findings

Based on the dashboard analysis:

1. **Category Performance:** Games dominate the market with approximately 31.54 billion installs, followed by Communication with 24.15 billion installs.
2. **Free vs Paid Apps:** Free applications account for approximately 92.61% of total app listings, while paid applications represent 7.39%.
3. **Average Rating:** The overall average app rating is approximately 4.19, indicating generally positive user feedback.
4. **Rating Distribution:** Most rated applications fall within the 4.0–4.4 rating group, followed by the 4.5–5.0 group.
5. **Content Rating:** The Everyone content rating dominates the dataset, with 8,382 application listings.
6. **User Engagement:** Free applications generate a higher average review volume than paid applications in the dataset.
7. **App Popularity:** The installs vs popularity visualization helps identify applications with different combinations of popularity and user ratings.

## 📁 Dataset Information

**Dataset:** Google Play Store Cleaned Dataset

The dataset contains application-level information, including:

- App Name
- Category
- Rating
- Reviews
- Installs
- Type
- Price
- Content Rating
- Size
- Genres
- Last Updated
- Current Version
- Android Version
- Sentiment-related metrics

The cleaned dataset also contains prepared analytical columns used for categorization and dashboard analysis.

## ⚙️ Data Preparation & Transformation

The following activities were performed during data preparation:

- Reviewed missing and inconsistent values.
- Checked data types and formatting.
- Standardized numerical fields.
- Prepared app size and installation categories.
- Created rating and price groupings.
- Prepared date-related fields for year-wise filtering.
- Validated application records and distinct app counts.
- Developed DAX measures for KPI calculations.

## 📈 Business Value

This dashboard demonstrates how application-level data can be converted into actionable insights.

It helps stakeholders:

- Identify high-performing app categories.
- Understand free and paid app distribution.
- Evaluate user engagement patterns.
- Explore the relationship between popularity and ratings.
- Identify opportunities for application market research.
- Make data-driven decisions using interactive reporting.

## ⚠️ Data Limitations

- The dataset contains a single last-updated date per app, so historical update frequency cannot be reliably calculated.
- Actual app revenue is not available; app prices should not be interpreted as generated revenue.
- Sentiment metrics are available only for a subset of application records.
- The dataset does not contain the original review text for detailed qualitative sentiment analysis.
- Repeated app names require careful handling when aggregating listing-level metrics.

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. If prompted, update the dataset source path.
4. Refresh the dataset.
5. Explore the dashboard using the available slicers and visual interactions.

## 📂 Suggested Repository Structure

```text
Google-Play-Store-App-Insights/
│
├── Dashboard/
│   └── Google_Play_Store_Insights.pbix
│
├── Dataset/
│   └── googleplaystore_cleaned.csv
│
├── Screenshots/
│   └── dashboard_overview.png
│
└── README.md
```

## 👨‍💻 Project Skills Demonstrated

- Data Cleaning & Transformation
- Power Query
- DAX Measures
- KPI Development
- Data Visualization
- Interactive Dashboard Design
- Exploratory Data Analysis
- Business Intelligence & Reporting
- Analytical Thinking

---

**Project:** Google Play Store – App Insights Dashboard  
**Tool:** Microsoft Power BI  
**Domain:** Mobile Applications / App Market Analytics  
**Project Type:** Business Intelligence & Data Analytics
