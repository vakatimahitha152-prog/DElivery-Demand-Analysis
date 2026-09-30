# QuickRoute Logistics Dashboard

## 📊 Project Overview

**QuickRoute Logistics Dashboard** is an interactive **Power BI
dashboard** designed to analyze last-mile delivery operations.

The dashboard provides a management-level view of:

-   Delivery demand and order trends
-   Delivery performance and reliability
-   Driver workload and performance
-   Vehicle utilization
-   Customer behavior
-   Failed deliveries and repeated delivery attempts
-   Delivery zones and service types

The project converts logistics data into interactive visual insights
that can support operational monitoring and resource planning.

------------------------------------------------------------------------

## 🎯 Project Objectives

The main objectives of this dashboard are to:

1.  Monitor overall delivery and order activity.
2.  Understand demand patterns across delivery zones.
3.  Measure delivery success and delivery duration.
4.  Identify failed deliveries and repeated delivery attempts.
5.  Analyze driver workload and delivery outcomes.
6.  Understand vehicle utilization across vehicle types.
7.  Analyze customer segments and order behavior.
8.  Provide an interactive executive summary for logistics operations.

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

-   **Microsoft Power BI**
-   **Power Query** -- Data preparation and transformation
-   **DAX** -- Measures and calculations
-   **Data Modeling** -- Relationships between logistics tables
-   **Interactive Visualizations** -- Charts, cards, gauges, slicers and
    drillthrough pages

------------------------------------------------------------------------

## 📁 Dashboard Pages

The Power BI report contains six main analytical pages.

### 1. Executive Summary

Provides a high-level management view of the logistics operation.

**Key metrics include:** - Total Orders - Total Deliveries - Total
Customers - Total Order Value - Active Drivers - Failed Deliveries -
Delivery Success %

**Key areas:** - Overall order activity - Delivery reliability - Vehicle
workload distribution - Operational problems - Key findings and
recommendations

------------------------------------------------------------------------

### 2. Delivery Demand

Analyzes where and how delivery orders are generated.

**Analysis includes:** - Total Orders - Total Order Value - Average
Order Value - Average Package Weight - Orders by Delivery Zone - Orders
by Customer Type - Orders by Service Type - Orders by Priority - Monthly
order trends

**Purpose:**

To understand high-demand zones, customer demand patterns and changes in
delivery volume over time.

------------------------------------------------------------------------

### 3. Delivery Performance

Measures delivery reliability and operational efficiency.

**Key metrics include:** - Total Deliveries - Delivery Success % -
Failed Deliveries - Average Delivery Duration

**Visual analysis includes:** - Delivery status distribution - Delivery
duration distribution - Delivery success trend - Delivery success by
zone - Average delivery duration

The dashboard also provides interactive filters for year, month,
delivery zone, service type and priority.

------------------------------------------------------------------------

### 4. Driver & Vehicle Performance

Evaluates driver workload, vehicle utilization and delivery outcomes.

**Key metrics include:** - Drivers With Deliveries - Average Driver
Rating - Deliveries per Driver - Deliveries per Vehicle - Delivery
Success %

**Visual analysis includes:** - Driver delivery distribution - Driver
workload vs. delivery duration - Driver delivery outcomes - Deliveries
by vehicle type - Overall vehicle delivery success

This page helps understand how delivery workload is distributed across
drivers and vehicles.

------------------------------------------------------------------------

### 5. Delivery Problems

Focuses on operational delivery issues.

**Key metrics include:** - Failed Deliveries - Failed Delivery % -
Pending Deliveries - Multiple Attempt Deliveries

**Analysis includes:** - Failed deliveries by month - Failed deliveries
by delivery zone - Multiple-attempt deliveries by zone - Delivery status
distribution - Average delivery attempts - Delivery success vs. delivery
attempts - Decomposition analysis of failed deliveries

The page also supports drillthrough analysis for delivery problem areas.

------------------------------------------------------------------------

### 6. Customer Behaviour

Analyzes customer participation and ordering behavior.

**Key metrics include:** - Total Customers - Average Order Value - Total
Revenue - Orders per Customer

**Analysis includes:** - Orders by customer type - Average order value
by customer type - Orders by delivery zone - Order value by delivery
zone - Customer order trends - Customer segment distribution

This page helps understand customer engagement and order-value patterns.

------------------------------------------------------------------------

## 📌 Key DAX Measures

The dashboard uses measures for important operational KPIs, including:

-   `Total Orders`
-   `Total Deliveries`
-   `Total Customers`
-   `Total Revenue`
-   `Total Order Value`
-   `Average Order Value`
-   `Average Package Weight`
-   `Orders per Customer`
-   `Delivery Success %`
-   `Average Delivery Duration`
-   `Failed Deliveries`
-   `Failed Delivery %`
-   `Multiple Attempt Deliveries`
-   `Pending Deliveries`
-   `Average Delivery Attempts`
-   `Drivers With Deliveries`
-   `Active Drivers`
-   `Deliveries per Driver`
-   `Deliveries per Vehicle`
-   `Average Driver Rating`

------------------------------------------------------------------------

## 📊 Visualizations Used

The report uses a combination of Power BI visuals:

-   KPI Cards
-   Bar Charts
-   Column Charts
-   Line Charts
-   Donut Charts
-   Treemaps
-   Scatter Charts
-   Gauges
-   Decomposition Trees
-   Slicers
-   Drillthrough pages

These visuals allow users to move from an overall operational view to
detailed analysis of zones, drivers, vehicles, customers and delivery
outcomes.

------------------------------------------------------------------------

## 🎛️ Interactive Filters

The dashboard provides filters such as:

-   Year
-   Month
-   Delivery Zone
-   Service Type
-   Priority

These filters allow users to analyze the logistics operation for
specific periods and operational segments.

------------------------------------------------------------------------

## 🔍 Key Insights Presented in the Dashboard

The dashboard highlights several operational observations, including:

-   Delivery demand shows an upward trend over the analyzed period.
-   Individual customers contribute a large share of orders.
-   Some delivery zones generate higher order volumes than others.
-   Delivery success varies across time and delivery zones.
-   Failed deliveries and multiple delivery attempts create additional
    operational effort.
-   Driver workload can be compared with delivery duration.
-   Vehicle utilization can be monitored using deliveries per vehicle.
-   Customer segments can be compared using order volume and average
    order value.

> **Note:** These observations are based on the data and calculations
> contained in the Power BI report and may change when the underlying
> data or filters are changed.

------------------------------------------------------------------------

## 🗂️ Data Entities Used

The report references logistics entities such as:

-   `orders`
-   `deliveries`
-   `customers`
-   `drivers`
-   `vehicles`
-   `date_table`
-   `_Measures`

Important fields used in the analysis include:

-   Customer Type
-   Delivery Zone
-   Service Type
-   Priority
-   Delivery Status
-   Delivery Duration
-   Driver ID
-   Vehicle Type
-   Delivery ID
-   Year
-   Month
-   Year-Month

------------------------------------------------------------------------

## 🔄 Dashboard Workflow

``` text
Logistics Data
      ↓
Data Preparation
      ↓
Power BI Data Model
      ↓
DAX Measures
      ↓
Interactive Visualizations
      ↓
Operational Analysis
      ↓
Business Insights
```

------------------------------------------------------------------------

## 💡 Business Use Cases

This dashboard can be used by logistics and operations teams to:

-   Monitor delivery demand
-   Track delivery performance
-   Identify problem zones
-   Monitor failed deliveries
-   Analyze repeated delivery attempts
-   Understand driver workload
-   Evaluate vehicle utilization
-   Compare customer segments
-   Support operational resource planning
-   Monitor logistics KPIs from a single dashboard

------------------------------------------------------------------------

## 📷 Dashboard Preview

The report uses an operations-focused Power BI layout with navigation
between the major analytical pages:

**Delivery Demand → Customer Behaviour → Delivery Performance → Driver &
Vehicle Performance → Delivery Problems → Executive Summary**

------------------------------------------------------------------------

## 🚀 How to Use the Project

1.  Download the Power BI project.
2.  Open the project in **Microsoft Power BI Desktop**.
3.  Review the **Executive Summary** page for the overall view.
4.  Use the navigation buttons to move between analytical pages.
5.  Apply Year, Month, Delivery Zone, Service Type and Priority filters.
6.  Select charts and data points to cross-filter other visuals.
7.  Use the Delivery Problems page for detailed issue analysis.
8.  Use Driver & Vehicle Performance to analyze operational capacity.

------------------------------------------------------------------------

## 📌 Project Highlights

-   Interactive logistics analytics dashboard
-   Six dedicated analytical pages
-   Multiple operational KPIs
-   Interactive slicers and navigation
-   Delivery problem analysis
-   Driver and vehicle performance analysis
-   Customer behavior analysis
-   Executive-level summary
-   Drillthrough analysis for delivery problems

------------------------------------------------------------------------

## 👩‍💻 Project Type

**Domain:** Logistics / Supply Chain Analytics\
**Category:** Data Analytics & Business Intelligence\
**Tool:** Microsoft Power BI\
**Dashboard:** QuickRoute Logistics\
**Focus:** Last-Mile Delivery Operations

------------------------------------------------------------------------

## 📄 Project Files

-   `QuickRoute_Logistics_Dashboard.pbix` -- Power BI dashboard project
-   `README.md` -- Project documentation

------------------------------------------------------------------------

## ⭐ Conclusion

The **QuickRoute Logistics Dashboard** provides an interactive view of
last-mile delivery operations by combining demand, performance,
customer, driver, vehicle and delivery-problem analysis in one Power BI
report.

It demonstrates practical use of **Power BI, Power Query, DAX, data
modeling and interactive visualization** for logistics business
intelligence.
