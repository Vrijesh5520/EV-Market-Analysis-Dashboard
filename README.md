# Electric Vehicle Market Analytics Dashboard

## Project Overview

This project presents a comprehensive Power BI dashboard for analyzing the global Electric Vehicle (EV) market using real-world inspired EV datasets. The dashboard provides insights into EV pricing, battery performance, charging capabilities, sales trends, vehicle specifications, customer ratings, and market segmentation.

The main objective of this project is to transform raw EV market data into interactive business intelligence dashboards that help stakeholders understand industry trends, customer preferences, and high-performing EV brands.

---

# Problem Statement

The Electric Vehicle industry is growing rapidly, with multiple manufacturers competing across various market segments such as Luxury, Mid-range, and Budget EVs. However, analyzing EV performance, pricing, battery efficiency, and customer demand manually becomes difficult due to the large volume of data.

This project solves the problem by:

* Providing interactive visual analytics for EV market analysis
* Identifying top-performing brands and models
* Comparing battery capacity, charging speed, and vehicle range
* Tracking annual sales performance
* Understanding customer satisfaction trends
* Supporting business decision-making using data visualization

---

# Dashboard Objectives

The dashboard is designed to:

* Analyze EV market trends across brands and countries
* Compare EV specifications and performance metrics
* Evaluate battery efficiency and charging technologies
* Identify top-selling electric vehicle models
* Study customer ratings and safety performance
* Visualize market segmentation and sales distribution
* Enable interactive filtering and exploration

---

# Technologies Used

* **Power BI Desktop** – Dashboard creation and data visualization
* **Microsoft Excel / CSV Dataset** – Data source
* **DAX (Data Analysis Expressions)** – Calculated measures and KPIs
* **Power Query** – Data cleaning and transformation

---

# Dataset Information

The dataset contains detailed information about electric vehicles from multiple global brands.

### Dataset Features

| Column Name           | Description              |
| --------------------- | ------------------------ |
| brand                 | EV manufacturer brand    |
| model                 | Vehicle model name       |
| year                  | Manufacturing year       |
| variant               | Vehicle variant          |
| price_usd             | Vehicle price in USD     |
| battery_capacity_kwh  | Battery capacity         |
| range_miles           | Driving range            |
| charging_speed_kw     | Charging speed           |
| acceleration_0_60_mph | Acceleration performance |
| top_speed_mph         | Maximum speed            |
| horsepower            | Vehicle horsepower       |
| torque_nm             | Torque output            |
| drive_type            | Drive configuration      |
| seating_capacity      | Number of seats          |
| body_type             | Vehicle body type        |
| cargo_volume_cubic_ft | Cargo space              |
| weight_kg             | Vehicle weight           |
| safety_rating         | Safety rating            |
| autopilot_level       | Automation level         |
| country_of_origin     | Manufacturing country    |
| market_segment        | Market category          |
| annual_sales_units    | Annual sales             |
| customer_rating       | Customer rating          |
| warranty_years        | Warranty duration        |

### Dataset Size

* Total Records: **2000**
* Total Features: **24**

---

# Dashboard Features

### KPI Cards

The dashboard includes important KPI indicators such as:

* Total EV Brands
* Total Models
* Average Vehicle Price
* Average Battery Capacity
* Average Vehicle Range
* Total Annual Sales
* Average Customer Rating

### Interactive Filters / Slicers

Users can dynamically filter data based on:

* Brand
* Model
* Year
* Market Segment
* Country of Origin

---

# Key Visualizations

## 1. Brand-wise Sales Analysis

Displays annual sales performance of different EV brands.

### Insights:

* Identifies top-selling EV manufacturers
* Compares market share between brands
* Tracks high-demand vehicle companies

---

## 2. Price vs Range Analysis

Analyzes the relationship between vehicle price and driving range.

### Insights:

* Helps identify value-for-money EVs
* Compares premium and budget segments
* Evaluates battery efficiency trends

---

## 3. Battery Capacity Analysis

Visualizes battery capacity distribution across different brands and models.

### Insights:

* Detects high-performance EV batteries
* Evaluates battery technology improvements
* Compares long-range EV capabilities

---

## 4. Charging Speed Comparison

Shows charging performance across EV brands.

### Insights:

* Identifies fastest charging EVs
* Helps compare charging technologies
* Supports infrastructure planning analysis

---

## 5. Market Segment Distribution

Analyzes EV distribution across:

* Luxury
* Premium
* Mid-range
* Budget segments

### Insights:

* Understands consumer demand by segment
* Helps businesses identify target markets

---

## 6. Customer Rating Analysis

Displays customer satisfaction trends.

### Insights:

* Identifies highly rated EV models
* Measures customer experience and reliability
* Supports quality improvement analysis

---

## 7. Country-wise EV Distribution

Shows the contribution of different countries in the EV market.

### Insights:

* Identifies leading EV manufacturing countries
* Analyzes global EV market expansion

---

# Power BI Workflow

## Step 1: Data Collection

* Imported EV dataset from CSV file
* Verified dataset structure and column consistency

## Step 2: Data Cleaning

Performed data preprocessing using Power Query:

* Checked missing values
* Verified data types
* Removed inconsistencies
* Standardized categorical fields

## Step 3: Data Transformation

* Created calculated columns
* Generated DAX measures
* Built KPIs for dashboard analysis

## Step 4: Dashboard Development

Created interactive visualizations using:

* Bar charts
* Pie charts
* Scatter plots
* KPI cards
* Line charts
* Slicers and filters

## Step 5: Insight Generation

Extracted meaningful business insights from visual analytics.

---

# Key Business Insights

* Luxury EVs generally offer higher battery capacity and longer range.
* Certain brands dominate global annual EV sales.
* Faster charging speed is strongly associated with premium EV segments.
* Customer ratings are higher for vehicles with better safety ratings and advanced autopilot features.
* Countries like the US, Germany, Japan, and South Korea contribute significantly to the EV market.
* Mid-range EVs show strong market competitiveness due to balanced pricing and features.

---

# Dashboard Screenshots

## Dashboard Overview

<img width="1321" height="743" alt="dashboard_overview" src="https://github.com/user-attachments/assets/9b7b93f1-57de-4347-84d6-e04556d4971d" />

## Sales Analysis

<img width="578" height="268" alt="sales_analysis" src="https://github.com/user-attachments/assets/a14bfa0c-26ee-4cb8-9ec1-1307470b865b" />

## Battery Capacity & Driving Range Analysis

<img width="1144" height="286" alt="battery_efficiency_ _driving_range_analysis" src="https://github.com/user-attachments/assets/e251ce8c-b93d-42b3-8343-329b52e64032" />

## Price vs Sales Analysis

<img width="590" height="282" alt="EV_price_vs_annual_sales_analysis" src="https://github.com/user-attachments/assets/fc5e4274-487b-4642-9e45-d8c54f75cf79" />

## Safety vs Satisfaction Analysis

<img width="580" height="283" alt="safety_vs_satisfaction_analysis" src="https://github.com/user-attachments/assets/3f80de69-766d-4e46-bddc-f73c5716722f" />

## Future Sales Prediction

<img width="573" height="275" alt="future_sales_prediction" src="https://github.com/user-attachments/assets/21ab056f-3b28-4077-b8d6-635eb6ee3959" />

## Warranty vs Customer Rating Analysis

<img width="570" height="276" alt="warranty_vs_customer_rating_analysis" src="https://github.com/user-attachments/assets/7c9e5498-fa90-4a0b-bcf5-bb7fa9eb2d29" />

## Top Model Reccomendation 

<img width="572" height="273" alt="model_recommendation_table" src="https://github.com/user-attachments/assets/85d690b6-59d0-4354-8ae3-45789a3eef88" />

---

# How to Run the Project

## Step 1

Download or clone the repository.

```bash
git clone https://github.com/your-username/EV-Market-Analytics-Dashboard.git
```

## Step 2

Open the `.pbix` file using:

* Power BI Desktop

## Step 3

Refresh the dataset if required.

## Step 4

Interact with dashboard filters and visualizations.

---

# Example Use Cases

This dashboard can be used by:

* Data Analysts
* EV Manufacturers
* Automotive Researchers
* Market Analysts
* Business Intelligence Teams
* Investors analyzing EV industry growth

---

# Future Improvements

* Add real-time EV market data integration
* Include charging station analytics
* Add forecasting and predictive analysis
* Build customer segmentation models
* Deploy dashboard to Power BI Service
* Add advanced DAX-based KPI analysis

---

# Learning Outcomes

Through this project, the following skills were demonstrated:

* Data Cleaning and Transformation
* Business Intelligence Dashboard Development
* Data Visualization Best Practices
* KPI and Metric Design
* Power BI Data Modeling
* Interactive Dashboard Design
* Business Insight Generation

---

# Conclusion

The Electric Vehicle Analytics Dashboard successfully converts raw EV market data into meaningful and interactive business insights. The project demonstrates strong Power BI skills, analytical thinking, and the ability to build professional dashboards for real-world business scenarios.

---

# Author

**Vrijesh S. Balam**
