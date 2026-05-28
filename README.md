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

```md
![Dashboard Overview](screenshots/dashboard_overview.png)
```

## Sales Analysis

```md
![Sales Analysis](screenshots/sales_analysis.png)
```

## Battery Capacity Analysis

```md
![Battery Analysis](screenshots/battery_analysis.png)
```

## Price vs Range Analysis

```md
![Price vs Range](screenshots/price_vs_range.png)
```

## Market Segment Analysis

```md
![Market Segment](screenshots/market_segment.png)
```

## Customer Rating Analysis

```md
![Customer Rating](screenshots/customer_rating.png)
```

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

**Vrijesh Balam**
