# Uber Data Analytics Dashboard

A comprehensive data visualization dashboard for analyzing Uber ride-sharing business metrics and performance indicators for the year 2024.

## 🎬 Project Showcase

<p align="center">
  <img src="Project%20Showcase/Dasboard.gif" alt="Dashboard Demo" width="600">
</p>

<div align="center">
  <h3><strong>Don't forget to leave a star ⭐️</strong></h3>
</div>

## 📊 Dashboard Overview

This interactive dashboard provides insights into various aspects of Uber's ride-sharing operations, including booking patterns, vehicle performance, revenue analysis, cancellation trends, and rating distributions.

### Key Metrics Summary (2024)
- **Total Bookings**: 148.77K
- **Success Rate**: 65.96% (93K completed rides)
- **Cancellation Rate**: 25% (37.43K cancelled bookings)
- **Customer Cancellations**: 19.15% (27K)
- **Driver Cancellations**: 7.45% (10.5K)


## ❓ Power BI Questions Solved

This comprehensive dashboard is organized into 5 strategic view segments, each addressing specific business analytics questions:

### 1. 📊 Overall Performance View
- **Ride Volume Over Time** - Time-series chart tracking daily/weekly ride patterns to identify seasonal trends and demand fluctuations
- **Booking Status Breakdown** - Pie/doughnut chart displaying proportions of completed, cancelled by customer, cancelled by driver, and other booking statuses

### 2. 🚗 Vehicle Type Analysis View  
- **Top 5 Vehicle Types by Ride Distance** - Table chart ranking vehicle types (Go Mini, Go Sedan, Auto, eBike/Bike, UberXL, Premier Sedan) based on total distance covered

### 3. 💰 Revenue Analytics View
- **Revenue by Payment Method** - Stacked bar chart breaking down revenue streams across payment channels (UPI, Cash, Credit Cards, Uber Wallet, Debit Card)
- **Top 5 Customers by Total Booking Value** - Leaderboard visualization identifying high-value customers and their spending patterns
- **Ride Distance Distribution Per Day** - Histogram plot revealing daily operational coverage patterns and distance distribution insights

### 4. 🚫 Cancellation Intelligence View
- **Cancelled Rides Reasons (Customer)** - Pie chart analysis examining customer-initiated cancellation drivers (Wrong Address, Change of Plans, Driver Issues, App Problems)
- **Cancelled Rides Reasons (Driver)** - Pie chart breakdown of driver-initiated cancellations (Customer Related Issues, Personal & Car Issues, Capacity Constraints)

### 5. ⭐ Rating & Quality Assessment View
- **Driver Ratings Distribution** - Card-based visualization displaying average driver ratings (4.23-4.24) across all vehicle types for easy comparison
- **Customer Ratings Analysis** - Card layout showcasing customer satisfaction ratings (4.40-4.41) across vehicle categories, enabling quality benchmarking


## 🚗 Vehicle Fleet Analysis

| Vehicle Type | Total Bookings | Success Bookings | Avg Distance | Total Distance |
|--------------|----------------|------------------|---------------|----------------|
| Go Mini      | 10.34M         | 9.41M           | 25.99 km      | 482K km        |
| Go Sedan     | 9.37M          | 8.54M           | 25.98 km      | 433K km        |
| Auto         | 12.88M         | 11.73M          | 25.99 km      | 602K km        |
| eBike/Bike   | 11.46M         | 10.44M          | 26.11 km      | 537K km        |
| UberXL       | 1.53M          | 1.41M           | 25.72 km      | 72K km         |
| Premier Sedan| 6.28M          | 5.73M           | 25.95 km      | 292K km        |


## 📈 Dashboard Views & Features

### 1. Overall Performance
- **Ride Volume Over Time**: Monthly trend analysis showing seasonal patterns
- **Booking Status Breakdown**: Pie chart visualization of booking outcomes
- Peak performance observed in July-August period
- Notable dip in February followed by steady growth

### 2. Vehicle Type Analysis
- Comprehensive breakdown of all vehicle categories
- Performance metrics by vehicle type
- Distance and booking value analysis
- Auto rickshaws leading in total bookings (12.88M)

### 3. Revenue Analytics
- **Revenue by Payment Method**: 
  - UPI: Highest revenue contributor (~2.0M)
  - Cash: Second highest (~1.1M)
  - Uber Wallet, Credit Card, Debit Card: Lower contributions
- **Top 5 Customers**: High-value customer identification
- **Daily Distance Distribution**: Consistent 6K-8K km range per day

### 4. Cancellation Analysis
#### Customer Cancellations (10.6K total)
- Wrong Address: 22.5% (2.36K)
- Change of Plans: 21.86% (2.3K)
- Driver Issues: 22.41% (2.35K)
- Driver Not Moving: 22.24% (2.34K)
- App Issues: 11% (1.16K)

#### Driver Cancellations (28K total)
- Customer Related Issues: 25.32% (7K)
- Customer Behavior: 24.76% (7K)
- Personal & Car Issues: 24.91% (7K)
- Capacity Issues: 25% (7K)

### 5. Rating System
#### Customer Ratings by Vehicle Type
- Consistent high ratings across all vehicle types: 4.40-4.41
- Go Sedan leading with 4.41 rating
- All other categories maintaining 4.40 rating

#### Driver Ratings by Vehicle Type
- Slightly lower than customer ratings: 4.23-4.24
- UberXL showing marginally higher driver satisfaction (4.24)
- Consistent performance across all vehicle categories


## 🔧 Data Schema

The dashboard is built using the following data columns:

```
- Date, Time
- Booking ID, Booking Status
- Customer ID, Vehicle Type
- Pickup Location, Drop Location
- Avg VTAT, Avg CTAT
- Cancelled Rides by Customer, Reason for cancelling by Customer
- Cancelled Rides by Driver, Driver Cancellation Reason
- Incomplete Rides, Incomplete Rides Reason
- Booking Value, Ride Distance
- Driver Ratings, Customer Rating
- Payment Method
```


## 📊 Key Visualizations

1. **Time Series Analysis**: Monthly ride volume trends
2. **Pie Charts**: Booking status and cancellation reason distributions
3. **Bar Charts**: Revenue by payment method, top customers
4. **Tables**: Vehicle type performance metrics
5. **Histograms**: Daily distance distribution patterns



## 🎯 Business Insights

### Strengths
- Strong customer satisfaction (4.40+ ratings)
- Diverse vehicle portfolio catering to different needs
- UPI adoption driving digital payments
- Consistent daily operations (6K-8K km coverage)

### Areas for Improvement
- 25% cancellation rate needs attention
- Driver satisfaction slightly lower than customer satisfaction
- Seasonal variations in ride volume
- Customer retention strategies for top spenders

<!-- 
<h2></h2>
<div align="center">
<strong>Thank you for exploring this dashboard! </strong>
<h3>If this project helped you, please consider giving it a ⭐️</h3>
</div> -->
