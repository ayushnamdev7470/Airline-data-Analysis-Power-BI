# ✈️ Airline Performance Analysis — Power BI

> 5 interactive dashboards for airline performance monitoring with Row-Level Security

## 📊 Dashboard Overview

| Dashboard | Tracks |
|-----------|--------|
| Passenger Analytics | Passenger count by airline |
| Booking Status | Confirmed / Cancelled / Pending tickets |
| Flight Performance | On-time vs delayed flights |
| Airline Comparison | Cross-airline performance metrics |
| Destination Analysis | Route-wise passenger distribution |

## 🔍 Overview
- Connected 3 tables: Flight, Passenger, Ticket Information
- FlightID used as primary key with One-to-Many relationships
- Slicers for Airline and Destination for drill-down filtering
- Flights classified as "Best" or "To Be Improved" based on on-time status
- Row-Level Security (RLS) configured for airline-specific data access

## ⚙️ Data Preparation
- Power Query: Removed duplicates, handled missing values
- DAX measure: Total Passengers
- DAX measure: Total Tickets Booked
- Conditional column: Flight performance classification

## 🛠️ Tech Stack
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-0078D4?style=flat-square)
![Power Query](https://img.shields.io/badge/Power_Query-Data_Prep-217346?style=flat-square)

## 📁 Files
| File | Description |
|------|-------------|
| `Airline_Analysis.pbix` | Main Power BI file with all dashboards and RLS config |
