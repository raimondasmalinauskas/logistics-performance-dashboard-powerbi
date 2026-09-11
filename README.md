# Logistics Performance Dashboard — Power BI

Interactive logistics performance dashboard developed in Microsoft Power BI to analyze warehouse, carrier and order-priority performance.

### 📊 Live Interactive Dashboard

[Open the Logistics Performance Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZmM0MWMyNGYtZjM1Ny00ZWYxLTljNjItYTkwOTEwMTBiOTZhIiwidCI6IjlhOWMwOTM4LWRjZWUtNGFlOS04ZmE1LTYyM2I0YWVkYTJkNyJ9)

[Download the Power BI project (.pbix)](./Logistics_Performance_Dashboard_PowerBI.pbix)

## Project Overview

This project demonstrates how operational logistics data can be transformed into an interactive business intelligence dashboard for monitoring order volume, order value, service performance and SLA compliance.

The dashboard is designed to help logistics and operations teams identify performance gaps, compare warehouses and carriers, and investigate operational trends.

## Dataset

The portfolio dataset contains:

- 25,000 orders
- 5 distribution centers
- 6 carriers
- Multiple order priorities and statuses
- Order value and operational performance data
- Data covering 2025–2026

The dataset is used for portfolio and demonstration purposes.

## Dashboard

### Overview

The Overview page provides a high-level view of logistics performance, including:

- Total orders
- Completed orders
- On-time dispatch
- SLA breach rate
- Total order value
- Monthly order trends
- Warehouse performance
- Carrier performance
- Priority performance

### Logistics Analysis

The Logistics Analysis page provides deeper operational analysis through:

- Warehouse performance summary
- Warehouse volume vs. order value
- Orders by carrier
- Order status by warehouse
- Orders by priority
- Order value by priority
- Interactive analysis-period filtering

## Key KPIs

| KPI | Result |
|---|---:|
| Total Orders | 25,000 |
| On-Time Dispatch | 95.23% |
| SLA Breach | 4.78% |
| Total Order Value | 245.9M DKK |
| Highest Monthly Order Value | 18.8M DKK |
| Best Value Month | May 2026 |

## Key Findings

### Express Orders

Express orders showed significantly lower on-time dispatch performance at 56.22% compared with 95.23% overall.

This identifies Express operations as an important area for further investigation.

### Warehouse Performance

Aalborg DC recorded the lowest on-time dispatch performance at 94.94% and the highest SLA breach rate at 5.13%.

### Warehouse Workload

Horsens DC handled the highest order volume with 7,053 orders while maintaining 95.24% on-time dispatch.

### Carrier Performance

DHL recorded the lowest on-time dispatch performance among the carriers at 94.72% and approximately 5.24% SLA breaches.

### Order Value

May 2026 was the highest-value month, generating approximately 18.8M DKK in order value.

## Data Model

The Power BI model uses a dimensional structure consisting of:

- FactOrders
- DimDate
- DimProduct
- DimWarehouse
- DimCustomer
- DimCarrier

DAX measures were developed for operational KPIs and analytical calculations.

## Tools & Technologies

- Microsoft Power BI
- DAX
- Data Modelling
- Power Query
- KPI Development
- Logistics Analytics
- Interactive Data Visualization

## Project Purpose

This project demonstrates the combination of logistics domain knowledge with data analytics and business intelligence skills to support operational decision-making.

## Screenshots

Screenshots of the dashboard will be added to this repository.
