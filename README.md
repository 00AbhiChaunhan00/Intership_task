
# 🚖 Goodcabs Business Performance & Passenger Analytics

**SQL | Microsoft Power BI | DAX | Data Modelling | Business Intelligence**

## 📌 Project Overview

This project focuses on analyzing Goodcabs' business performance across **10 Indian cities over six months (January–June 2026)** using SQL and Microsoft Power BI.

The objective is to transform trip and passenger data into actionable business insights by evaluating revenue performance, city-level operations, passenger acquisition, repeat behaviour, and target achievement.

The project combines SQL-based business analysis with an interactive, three-page Power BI dashboard to support data-driven decision-making.

## 🎯 Business Objectives

- Analyze overall trip and revenue performance.
- Identify high-performing cities based on revenue and trips.
- Compare actual trip performance against monthly targets.
- Understand new and repeat passenger behaviour.
- Evaluate repeat passenger contribution and frequency.
- Monitor passenger ratings against city targets.
- Identify business trends and areas requiring improvement.

## 📊 Dataset Overview

The project uses eight datasets covering trip transactions, passenger summaries, city information, dates, repeat-trip distribution, and business targets.

| Dataset | Description |
|---|---|
| `fact_trips` | Individual trip-level transaction data |
| `fact_passenger_summary` | Monthly new, repeat, and total passenger information |
| `dim_city` | City details |
| `dim_date` | Date, month, and day-type information |
| `dim_repeat_trip_distribution` | Repeat passenger trip frequency |
| `monthly_target_trips` | Monthly trip targets by city |
| `monthly_target_new_passengers` | Monthly new passenger targets |
| `city_target_passenger_rating` | Target passenger ratings by city |

**Data Coverage:**
- Reporting Period: January–June 2026
- Cities Covered: 10
- Total Trip Records: Approximately 426K

## 🛠️ Tools & Technologies

- **MySQL:** Data exploration, querying, aggregations, and business analysis.
- **Microsoft Power BI:** Interactive dashboard development and visualization.
- **DAX:** KPI calculations, performance metrics, and target achievement analysis.
- **Data Modelling:** Connecting fact and dimension tables to support analytical reporting.

## 🔍 SQL Business Analysis

The SQL analysis addresses six key business areas:

1. **City Performance:** Evaluate revenue and trip performance across cities.
2. **Monthly Trips vs Targets:** Compare actual trips against monthly targets.
3. **Repeat Passenger Frequency:** Understand how frequently repeat passengers travel.
4. **New Passenger Rankings:** Identify cities performing well in new passenger acquisition.
5. **Peak Demand Analysis:** Identify months with higher trip demand.
6. **Repeat Passenger Rate:** Measure repeat passenger contribution.

**SQL Concepts Applied:**
- SELECT, WHERE, GROUP BY and HAVING
- Aggregate Functions
- JOIN Operations
- Subqueries
- Window Functions

## 📈 Power BI Dashboard

The interactive dashboard consists of three analytical pages.

### 1. General View

Provides an overall summary of business performance.

**Key KPIs:**
- Total Trips
- Total Revenue
- Total Distance Travelled
- Average Passenger Rating
- Average Fare per Trip
- Average Fare per Km
- Average Trip Distance
- Maximum and Minimum Trip Distance
- Total, New and Repeat Passengers
- Repeat Passenger Rate (RPR%)
- Monthly Revenue Growth
- New vs Repeat Trips Ratio

**Visualizations:**
- Monthly Revenue & Trips Trend
- Monthly Revenue Growth Rate
- New vs Repeat Passenger Trips
- Actual Trips vs Target Trips
- Revenue by City
- Monthly New vs Repeat Passenger Trend

### 2. City Performance

Focuses on city-level business performance and target achievement.

**Key Analysis:**
- City-wise revenue and trip performance
- Monthly performance trends
- Actual Trips vs Target Trips
- New Passengers vs Target New Passengers
- Average Passenger Rating vs Target Rating
- Target Achievement Rates

### 3. Passenger Type & Repeat Behaviour

Analyzes passenger acquisition and repeat travel patterns.

**Key Analysis:**
- New vs Repeat Passenger Segmentation
- Total, New and Repeat Passengers
- Repeat Passenger Rate (RPR%)
- New vs Repeat Passenger Trips Ratio
- Repeat Passenger Trip Frequency
- Monthly Passenger Behaviour Trends

**Interactive Filters:**
- City
- Month
- Day Type
- Passenger Type

## 💡 Key Business Insights

The analysis highlights several important findings:

- Approximately **425.9K trips** were recorded during the analysis period.
- Total fare revenue reached approximately **₹108.19 million**.
- The average fare per trip was approximately **₹254.02**.
- The average passenger rating was **7.66**.
- Jaipur generated the highest revenue among the analyzed cities, at approximately **₹37.21 million**.
- Repeat passenger trips accounted for approximately **58.44%** of total trips.
- Repeat passengers represented approximately **25.7%** of total passengers.
- New passenger numbers declined from approximately 35K in January to 23K in June.

## 🎯 Business Recommendations

1. **Improve New Passenger Acquisition:** Investigate the decline in new passenger numbers and strengthen customer acquisition campaigns.
2. **Encourage Repeat Trips:** Introduce loyalty programs and targeted offers to improve passenger retention.
3. **Focus on High-Performing Cities:** Understand successful operating patterns in cities generating higher revenue.
4. **Monitor Target Achievement:** Regularly compare actual performance against city-level monthly targets.
5. **Investigate Revenue Trends:** Analyze monthly revenue changes and identify opportunities to improve performance.

## 📁 Project Deliverables

- SQL business analysis queries.
- Power BI interactive dashboard.
- DAX-based KPIs and performance calculations.
- Data model and relationships.
- Business insights and recommendations.

## 🚀 Conclusion

This project demonstrates how SQL and Power BI can be used together to solve practical business problems.

By analyzing trip transactions, revenue, passenger behaviour, and target performance, the dashboard provides a consolidated view of Goodcabs' business operations and supports more informed business decisions.

---

**Developed as part of the Codebasics Data Analytics Internship Project.**

**Tools:** MySQL | Microsoft Power BI | DAX
