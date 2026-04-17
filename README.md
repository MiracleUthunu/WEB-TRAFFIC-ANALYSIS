# Global Web Traffic Analysis

> A Power BI-driven web traffic intelligence dashboard designed to uncover user behavior, engagement quality, and market-level performance trends.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi\&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-Data%20Preparation-336791?logo=postgresql\&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-blue)

## Project Overview

The Global Web Traffic Analysis project is an interactive business intelligence solution built to analyze website traffic, engagement quality, and market performance across multiple domains and regions. Using Power BI, the project transforms raw traffic data into a clear, decision-oriented dashboard that helps stakeholders identify high-performing markets, understand visitor behavior, and detect opportunities to improve digital performance.

The dashboard was developed with a strong focus on business storytelling, allowing users to move from high-level KPIs to deeper insights around engagement, traffic sources, and market efficiency.

## Problem Statement

Organizations often collect large amounts of website traffic data but struggle to translate it into actionable business insights. Raw metrics such as visits, bounce rates, or session durations alone do not clearly explain:

* Which markets generate the highest-quality traffic
* Which website categories are underperforming
* Whether increasing traffic is leading to stronger engagement
* How efficiently different regions convert traffic into meaningful activity

Without a structured dashboard, decision-makers may miss critical patterns that affect marketing spend, user acquisition strategy, and overall website performance.

## Objectives

* Analyze global web traffic performance across different markets and website categories
* Measure traffic quality using engagement metrics such as bounce rate, pages per visit, and average visit duration
* Compare performance between regions, domains, and categories
* Identify high-performing and underperforming markets
* Build an interactive dashboard that supports business decision-making
* Present insights in a clean, recruiter-ready Power BI project portfolio

## Tools & Technologies

| Tool                | Purpose                                                          |
| ------------------- | ---------------------------------------------------------------- |
| Power BI            | Built the interactive dashboard and visualizations               |
| Power Query         | Cleaned, transformed, and prepared the raw dataset               |
| DAX                 | Created calculated measures, KPIs, and custom metrics            |
| SQL                 | Structured and explored the data before visualization            |
| Excel / CSV Dataset | Source of the raw web traffic records                            |
| Data Modeling       | Connected domain, market, and category tables into a star schema |

## Dataset Information

The project uses a global web traffic dataset containing website performance information across different domains, markets, and categories.

The dataset includes:

* Website domain names
* Geographic market or region
* Website category
* Total visits
* Pages per visit
* Average session duration
* Bounce rate
* Traffic share and engagement indicators

The data model was organized into the following tables:

* `Dim_Domain`
* `Dim_Market`
* `Dim_Category`
* `Fact_Table`

Before analysis, the dataset was cleaned and prepared by:

* Removing duplicates and missing values
* Standardizing category and market names
* Converting metrics into the correct numeric and percentage formats
* Creating relationships between dimension and fact tables
* Building calculated columns and DAX measures for KPI reporting

## Methodology / Process

### 1. Data Collection

The raw traffic data was imported into Power BI from the source dataset and reviewed to understand its structure, fields, and quality.

### 2. Data Cleaning

Using Power Query and SQL:

* Missing values were handled
* Duplicate records were removed
* Column names were standardized
* Inconsistent categories and market names were corrected
* Data types were assigned correctly

### 3. Data Analysis

The analysis focused on identifying:

* Markets with the highest traffic volume
* Regions with the strongest engagement quality
* Categories with high bounce rates or weak performance
* Relationships between visit volume and engagement metrics

### 4. Visualization & Dashboard Development

A multi-page Power BI dashboard was created with two core sections:

1. **Traffic & Engagement Quality**

   * Website traffic trends
   * Bounce rate analysis
   * Session duration and pages-per-visit metrics
   * Top-performing domains and categories

2. **Market & Performance Efficiency**

   * Regional performance comparison
   * Traffic contribution by market
   * Identification of efficient and underperforming regions
   * Comparative KPI analysis across markets

### 5. Final Results

The completed dashboard provides a centralized view of global website performance and enables stakeholders to quickly identify where optimization efforts should be focused.

## Features

* Interactive multi-page Power BI dashboard
* Dynamic filtering by market, category, and domain
* KPI cards for traffic, engagement, and efficiency metrics
* Comparative analysis across different regions
* Drill-down functionality for deeper investigation
* Traffic quality analysis using bounce rate and session duration
* Responsive visual layout designed for easy storytelling

## Key Findings / Results

* Some markets generated high traffic volumes but had poor engagement quality, indicating inefficient acquisition strategies.
* Certain website categories achieved lower traffic but significantly better engagement, suggesting stronger audience relevance.
* Bounce rate varied noticeably between markets, highlighting regions that may require content or UX improvements.
* A small number of domains contributed disproportionately to total traffic, making them key drivers of overall performance.
* Pages per visit and session duration proved more reliable indicators of quality than total traffic alone.

## Screenshots / Preview

> Replace the placeholders below with screenshots exported from your Power BI dashboard.

![Dashboard Preview](images/dashboard-preview.png)

![Traffic & Engagement Page](images/traffic-engagement.png)

![Market Performance Page](images/market-performance.png)

## Project Structure

```text
global-web-traffic-analysis/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── dashboard/
│   └── GLOBAL WEB TRAFFIC ANALYSIS.pbit
│
├── images/
│   ├── dashboard-preview.png
│   ├── traffic-engagement.png
│   └── market-performance.png
│
├── sql/
│   └── traffic_analysis_queries.sql
│
├── docs/
│   └── project-summary.pdf
│
├── README.md
└── requirements.txt
```

## Installation & Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/global-web-traffic-analysis.git
```

2. Open the project folder:

```bash
cd global-web-traffic-analysis
```

3. Open the `.pbit` or `.pbix` file in Power BI Desktop.

4. If prompted, connect the dashboard to the dataset source.

5. Refresh the data and explore the report pages using the available filters and slicers.

6. Optional: Run the SQL scripts in the `sql/` folder to reproduce the data preparation process.

## Future Improvements

* Add time-series analysis to track traffic growth and engagement changes over time
* Integrate additional traffic sources such as social media, paid campaigns, and referral traffic
* Build predictive models to forecast future traffic trends
* Publish the dashboard to Power BI Service for live web access
* Add automated data refresh and scheduled reporting

## Why This Project Matters

This project demonstrates practical skills that employers value in data and business intelligence roles, including:

* Data cleaning and transformation
* Data modeling and relationship building
* DAX measure creation
* Dashboard design and storytelling
* Business problem solving through analytics
* Converting complex datasets into clear, actionable insights

For recruiters and hiring managers, this project showcases the ability to work end-to-end on a real-world analytics solution—from raw data preparation to polished business presentation.

## Author

**Miracle Ufuoma Uthunu**

* LinkedIn: [https://www.linkedin.com/in/miracle-uthunu/](https://www.linkedin.com/in/your-linkedin-profile)
* GitHub: [https://github.com/MiracleUthunu](https://github.com/your-github-username)
* Email: [miracleuthunu@gmail.com](mailto:your.email@example.com)
