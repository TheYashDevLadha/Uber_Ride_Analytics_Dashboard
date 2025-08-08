# Uber Ride Analytics Dashboard

A comprehensive data visualization dashboard for analyzing Uber ride-sharing business metrics and performance indicators for the year 2024.

## 🎬 Project Showcase

![Dashboard Demo](demo.gif)

> **Don't forget to leave a star ⭐️**

## 📊 Dashboard Overview

This interactive dashboard provides insights into various aspects of Uber's ride-sharing operations, including booking patterns, vehicle performance, revenue analysis, cancellation trends, and rating distributions.

### Key Metrics Summary (2024)
- **Total Bookings**: 148.77K
- **Success Rate**: 65.96% (93K completed rides)
- **Cancellation Rate**: 25% (37.43K cancelled bookings)
- **Customer Cancellations**: 19.15% (27K)
- **Driver Cancellations**: 7.45% (10.5K)

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

## ❓ Power BI Questions Solved

This dashboard addresses the following analytical questions with specific visualization techniques:

1. **Ride Volume Over Time** - A time-series chart showing the number of rides per day/week
2. **Booking Status Breakdown** - A pie or doughnut chart displaying the proportion of different booking statuses (success, cancelled by the customer, cancelled by the driver, etc.)
3. **Top 5 Vehicle Types by Ride Distance** - A bar chart ranking vehicle types based on the total distance covered
4. **Average Customer Ratings by Vehicle Type** - A column chart showing the average customer ratings for different vehicle types
5. **Cancelled Rides Reasons** - A bar chart that highlights the common reasons for ride cancellations by customers and drivers
6. **Revenue by Payment Method** - A stacked bar chart displaying total revenue based on payment methods (Cash, UPI, Credit Card, etc.)
7. **Top 5 Customers by Total Booking Value** - A leaderboard visual listing customers who have spent the most on bookings
8. **Ride Distance Distribution Per Day** - A histogram or scatter plot showing the distribution of ride distances for different dates
9. **Driver Rating Distribution** - A box plot visualizing the spread of driver ratings for different vehicle types
10. **Customer vs. Driver Ratings** - A scatter plot comparing customer and driver ratings for each completed ride, analyzing correlations

---

**Note**: This dashboard represents data for the period January 1, 2024 to December 30, 2024, providing a comprehensive year-long analysis of Uber's ride-sharing operations.
