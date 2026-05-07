# AI-Powered Fleet Performance & Delivery Efficiency Dashboard

---

# Objective

This project focuses on building an AI-powered transport operations dashboard using Power BI to analyze fleet performance, delivery efficiency, fuel usage, and transportation costs.

The main objectives of this project are:

- Analyze delivery performance across destinations
- Monitor fuel efficiency trends
- Evaluate transportation cost efficiency
- Identify factors affecting on-time delivery
- Optimize fleet utilization using AI-powered insights

---

# Dataset Information

- Domain: Logistics & Transportation
- Tool Used: Power BI
- Dataset Type: Trip Data and Vehicle Master Data

## Tables Included

- Trip_Data
- Vehicle_Master

---

# Tools Used

## Power BI

Used for:

- Data cleaning
- Data transformation
- Data modeling
- DAX measure creation
- Dashboard development
- AI-powered visualizations

## Power Query

Used for:

- Handling missing values
- Replacing null values
- Data type validation
- Data preparation and transformation

---

# Data Cleaning and Preparation

The following preprocessing steps were performed:

- Identified missing values in Fuel_Consumed_L column
- Replaced null fuel values using average fuel consumption
- Validated data types
- Reviewed unnecessary blank rows
- Applied required transformations using Power Query
- Loaded cleaned data into Power BI model using Close & Apply

---

# Data Modeling

A relationship was created between Trip_Data and Vehicle_Master tables using Vehicle_ID.

## Relationship Details

- One-to-Many (1:*) relationship created
- Duplicate and blank entries removed
- Data model optimized for filtering and analysis

---

# DAX Measures Created

## Measure 1: Fuel Efficiency

This measure calculates:

- Total Distance Travelled / Total Fuel Consumed

Purpose:
- Evaluate vehicle fuel performance
- Analyze fuel utilization efficiency

---

## Measure 2: On-Time Delivery %

This measure calculates:

- Percentage of on-time deliveries compared to total trips

Purpose:
- Evaluate delivery reliability
- Measure operational efficiency

---

## Measure 3: Cost per km

This measure calculates:

- Total Operational Cost / Total Distance Travelled

Purpose:
- Analyze transportation cost efficiency
- Identify operational cost performance

---

## Measure 4: Average Delivery Time

Average delivery time was approximated using average trip distance due to the absence of delivery duration data.

Purpose:
- Estimate delivery effort across trips

---

# Dashboard Visualizations

The dashboard includes the following visuals:

- KPI Cards
- Bar Chart
- Line Chart
- Pie Chart
- Key Influencers Visual
- Decomposition Tree
- Q&A Visual
- Interactive Slicer

---

# KPI Cards

The dashboard displays:

- Average Delivery Time
- Average Cost per km

These KPIs provide a quick overview of operational and transportation efficiency.

---

# Dashboard Insights

The dashboard provides insights into:

- On-Time Delivery % by Destination
- Fuel Efficiency by Delivery Date
- Maintenance Cost by Vehicle Type
- Cost per km Analysis
- Vehicle Performance Analysis
- Delivery Reliability
- Transportation Cost Drivers

---

# AI-Powered Visuals

## Key Influencers Visual

Used to identify factors affecting delivery status such as:

- Driver ID
- Distance
- Vehicle Type

---

## Decomposition Tree

Used to analyze:

- Cost per kilometer
- Maintenance cost
- Distance travelled
- Vehicle type impact

---

## Q&A Visual

Allows users to ask business questions using natural language queries and receive instant insights.

---

# Interactive Filtering

A slicer was added for:

- Vehicle Type

This allows users to compare fleet performance across:

- Truck
- Van
- Mini-Truck

---

# Key Insights

- Fuel efficiency trends help identify operational inefficiencies
- Certain destinations have lower on-time delivery performance
- Maintenance costs vary across vehicle types
- AI visuals help identify major cost drivers
- Vehicle type impacts transportation efficiency
- Interactive filtering improves analysis flexibility

---

# Conclusion

This project demonstrates the practical application of Power BI, Power Query, DAX measures, and AI-powered visuals for logistics and transportation analysis.

The dashboard provides meaningful insights into delivery performance, fuel efficiency, fleet utilization, and transportation costs, supporting data-driven operational decision-making.
