## Hospitality Revenue Analytics Dashboard 


# Project Overview

This Power BI dashboard provides comprehensive revenue analytics for AtliQ Grands, a chain of luxury and business hotels across India. The solution was developed to help management regain market share by making data-driven decisions based on historical performance metrics.

# Business Context
AtliQ Grands has been facing:

Declining market share in the luxury/business hotel category

Revenue losses due to ineffective decision-making

Intense competition in key markets

This dashboard provides the data intelligence needed to reverse these trends.

# Key Features

1. Performance Metrics Tracking
Revenue: Total generated and realized revenue across properties

RevPAR: Revenue Per Available Room

ADR: Average Daily Rate

Occupancy %: Room utilization rates

Realization %: Percentage of potential revenue captured

Cancellation %: Booking cancellation rates

Guest Ratings: Customer satisfaction metrics

2. Interactive Visualizations
Property-wise performance comparison

City-level analytics

Room category (Luxury vs Business) analysis

Weekly trend tracking (May-July 2022)

Weekend vs weekday performance comparison

Booking platform effectiveness

3. Advanced Analytics
Revenue waterfall by week and category

Occupancy vs ADR correlation analysis

Realization percentage by booking channel

Cancellation impact on revenue

# Data Sources
The dashboard integrates data from multiple tables:

dim_date: Date dimensions with week numbers

dim_hotels: Property information including cities and categories

dim_rooms: Room type classifications

fact_aggregated_bookings: Capacity and successful bookings

fact_bookings: Detailed transaction records

# How to Use the Dashboard
Executive Summary: Start with the KPI cards for an overview

Property Drill-down: Filter by city or property for detailed analysis

Time Analysis: Examine weekly trends using the time filters

Category Comparison: Compare Luxury vs Business performance

Channel Effectiveness: Evaluate different booking platforms

# Key Insights Identified
# Revenue Opportunities:

24.84% average cancellation rate represents significant revenue leakage

Weekend occupancy is 6.79% higher than weekdays

Luxury properties show higher ADR but similar occupancy to business hotels

# Performance Variations:

Mumbai properties generate the highest revenue

Bangalore Atliq Blu shows unusually low occupancy (53.25%) compared to peers

Direct online bookings have highest realization rates (70.57%)

# Seasonal Patterns:

Week 22 showed peak revenue performance

Gradual decline in occupancy from May to July

Technical Implementation
Developed in Power BI Desktop

Data modeling with star schema

DAX measures for custom metrics

Responsive design for different viewing devices

Bookmarks for guided navigation

Files Included
AtliQ_Grands_Analytics.pbix: Main Power BI file

Sample_Data/: Folder with CSV data sources

Documentation/: Additional context files

Requirements
Power BI Desktop (version 2.109 or later recommended)

Basic understanding of hospitality metrics
