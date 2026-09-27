# Digital-advertising-performance-Powerbi
Digital Advertising Performance Analysis using Excel, Power Query, DAX and Microsoft Power BI.
📌 Project Overview

This project analyzes digital advertising performance using Microsoft Excel, Power Query, DAX, and Microsoft Power BI.

The objective is to evaluate advertising campaigns and platforms using key business metrics such as Spend, Revenue, Impressions, Clicks, Conversions, CTR, CPC, Conversion Rate, and ROAS.
The project includes data preparation, cleaning, analytical calculations, interactive dashboards, and business insights.

🎯 Project Objectives

Analyze digital advertising campaign performance.
Compare performance across advertising platforms.
Measure campaign efficiency using important marketing KPIs.
Analyze advertising spend, revenue, clicks, and conversions.
Build an interactive Power BI dashboard.
Practice data cleaning and transformation using Power Query.
Create calculated business measures using DAX.
Develop practical Business Intelligence and Data Analytics skills.

🛠️ Tools & Technologies

Microsoft Excel – Dataset storage and initial inspection
Power Query – Data cleaning and transformation
Microsoft Power BI – Interactive dashboard and visualization
DAX – Calculated measures
Data Visualization – KPI cards, bar charts, column charts, line charts, matrix and slicers

📂 Dataset

The project dataset contains 1,460 advertising records and 12 fields:
Field
Description
Date
Advertising activity date
Platform
Advertising platform
Campaign
Campaign name
Ad Type
Type of advertisement
Objective
Campaign objective
Region
Geographic region
Device
Device used by the audience
Impressions
Number of times ads were displayed
Clicks
Number of ad clicks
Spend
Advertising expenditure
Conversions
Number of successful conversions
Revenue
Revenue generated

The dataset contains no missing values and no duplicate complete rows after validation.

🔄 Data Preparation & Cleaning

The dataset was prepared using Power Query in Power BI.
Imported the Excel dataset into Power BI.
Inspected column quality.
Checked for missing values.
Verified data types.
Checked duplicate records.
Applied duplicate-row removal across the complete dataset.
Checked for errors.
Applied the cleaned data to the Power BI model.
Data Types
Date → Date
Platform, Campaign, Ad Type, Objective, Region, Device → Text
Impressions, Clicks, Conversions → Whole Number
Spend, Revenue → Decimal Number

📐 DAX Measures

Total Spend

Total Spend = SUM(Advertising_Data[Spend])

Total Revenue

Total Revenue = SUM(Advertising_Data[Revenue])

Total Impressions

Total Impressions = SUM(Advertising_Data[Impressions])

Total Clicks

Total Clicks = SUM(Advertising_Data[Clicks])

Total Conversions

Total Conversions = SUM(Advertising_Data[Conversions])

CTR

CTR =
DIVIDE(
    [Total Clicks],
    [Total Impressions],
    0
)

CPC

CPC =
DIVIDE(
    [Total Spend],
    [Total Clicks],
    0
)

Conversion Rate

Conversion Rate =
DIVIDE(
    [Total Conversions],
    [Total Clicks],
    0
)

ROAS

ROAS =
DIVIDE(
    [Total Revenue],
    [Total Spend],
    0
)

📊 Dashboard

1. Executive Overview

The Executive Overview provides:
Total Spend
Total Revenue
Total Impressions
Total Clicks
Total Conversions
ROAS
Revenue by Platform
Spend by Platform
Monthly Revenue Trend
Conversions by Campaign

2. Campaign Analysis

The Campaign Analysis page provides:
Revenue by Campaign
ROAS by Campaign
Conversions by Campaign
Spend by Campaign
CTR by Campaign
Platform × Campaign Matrix
Campaign Slicer
Platform Slicer

The slicers allow interactive filtering of campaign and platform combinations.

📈 Overall KPI Results

KPI
Result
Total Spend
₹1,157,127.00

Total Revenue
₹15,941,949.44

Total Impressions
2,445,529

Total Clicks
69,430

Total Conversions
5,323

CTR
2.84%

CPC
₹16.67

Conversion Rate
7.67%

ROAS
13.78

📊 Platforms Analyzed

Meta Ads
Google Ads
YouTube Ads
LinkedIn Ads

🎯 Campaigns Analyzed

Retargeting
Brand Awareness
Summer Sale
New Product Launch
Festive Offer
Lead Generation

🔍 Key Analytical Questions

The dashboard helps answer:
How much total revenue was generated?
How much advertising spend was used?
How do platforms compare in revenue and conversions?
How do campaigns compare using ROAS and CTR?
What are the overall CTR, CPC and Conversion Rate?
How does performance change when filtering by campaign?
How does platform performance vary across campaigns?


💡 Skills Demonstrated

Data Analytics: Data cleaning, validation, KPI analysis, business analysis and interpretation.

Power BI: Data import, Power Query, DAX, KPI cards, interactive visualizations, slicers, matrix analysis and dashboard design.

Excel: Dataset handling, data inspection and data dictionary interpretation.

👨‍💻 Author

Yash Jonwal
B.Tech – Computer Science Applications
Vivekananda Global University

⭐ End-to-End Workflow

Excel → Power Query → DAX → Power BI → Interactive Dashboard → Business Analysis
