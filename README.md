#  911 Emergency Calls Dashboard – Power BI Project

This Power BI project analyzes 660K+ emergency call records to uncover patterns in EMS, Fire, and Traffic incidents across zip codes in Montgomery County, PA. The goal is to help emergency services optimize response strategies, resource allocation, and preparedness based on call volumes, time trends, and geographic hotspots.

---

##  Objective

To visualize and analyze emergency call data using Power BI, identify key trends by call type, location, and time, and deliver actionable insights for improving emergency response systems.

---

##  Dataset Overview

- **Source**: [Kaggle - 911 Calls Dataset](https://www.kaggle.com/datasets/mchirico/montcoalert)
- **Rows**: 663,522  
- **Key Features**:
  - `lat`, `lng` – GPS Coordinates  
  - `zip`, `title`, `timeStamp`, `twp`, `addr`, `e`  
  - `title` contains department and reason

---

##  Tools & Skills Used

- Power BI (DAX, Data Modeling, Visuals)
- Data Cleaning & Transformation
- Exploratory Data Analysis (EDA)
- Date-Time Analysis
- KPI Building & Trend Detection

---

##  Data Model – Key Columns Created

- `Call Type` (extracted from `title`)
- `Hour`, `Day`, `Month`, `Year`, `Day of Week` (from `timeStamp`)
- `Emergency Category`: Fire, EMS, or Traffic
- `Zip Group` (for better visual grouping)

---

##  Key DAX Measures

- Total Calls  
- % of Calls by Type  
- Calls by Zip  
- Calls by Hour / Day / Month  
- Trend Over Time (Line Graph)
- Decomposition Tree for Deep Dive

---

##  Project Highlights

- **Heatmap** showing call density across hours and days
- **Decomposition Tree** breaking down total calls by zip code
- **Custom KPIs** tracking call volumes per department
- **Time Series Trends** by month/year
- **Top Zip Codes & Townships** with highest emergency calls
- **Clean UI with Minimalist Theme**

---

## 📌 Insights & Business Goals

| Insight | Goal |
|--------|------|
| EMS is the most frequent emergency type | Prioritize medical staff deployment |
| Peak call hours: 12 PM to 6 PM | Increase dispatch readiness during peak |
| Zip code 19401 leads in call volume | Resource allocation & station proximity improvement |
| Fire-related calls spike on weekends | Fire safety awareness campaigns on weekends |
| Traffic calls mostly during weekdays, 7–9 AM | Traffic control & accident prevention planning |

---

##  Outcomes & Value

- Created a professional, recruiter-ready dashboard  
- Simulated real-life emergency service analysis  
- Demonstrated ability to extract business insights from raw data  
- Developed storytelling and visual analytics capability  
- Suitable for portfolio, resume, and interviews



---

##  Thank You

This project reflects my learning journey in data storytelling, dashboard design, and real-world problem solving using Power BI.

---
