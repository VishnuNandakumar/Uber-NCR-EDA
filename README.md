# Uber NCR Ride Bookings - Exploratory Data Analysis (EDA)

## Project Overview
This project performs an **end-to-end Exploratory Data Analysis (EDA)** on Uber ride bookings in the **National Capital Region (NCR)**.  
The goal is to uncover **ride patterns, customer behavior, demand trends, and service quality insights** to provide **data-driven recommendations** for improving efficiency, customer satisfaction, and revenue optimization.  

---

## Objectives
- Analyze **ride demand patterns** by time, day, and location.  
- Study **fare distribution and distance trends**.  
- Explore **payment preferences** of customers.  
- Identify **peak vs off-peak demand**.  
- Understand **cancellation trends** (customer vs driver).  
- Evaluate **service ratings** for drivers and customers.  
- Provide **business recommendations** for optimization.  

---

## Dataset
- **File Name:** `ncr_ride_bookings.xlsx`  
- **Rows:** ~150,000  
- **Columns:** 21  
- **Key Columns:**  
  - Date, Time  
  - Booking ID, Booking Status  
  - Pickup & Drop Locations  
  - Booking Value, Ride Distance  
  - Driver Ratings, Customer Ratings  
  - Payment Method  

---

## Exploratory Data Analysis

### Univariate Analysis
- Ride Distance Distribution  
- Fare Distribution  
- Payment Preferences  
- Popular Vehicle Types  

### Bivariate Analysis
- Fare vs Distance  
- Ride Demand by Day of Week  
- Cancellations (Customer vs Driver)  
- Average Fare by Day  

### Multivariate Analysis
- Correlation Heatmap (numeric features)  
- Heatmap of Ride Demand by **Hour vs Day of Week**  

---

## Key Observations
1. Ride demand peaks during **8–10 AM & 6–9 PM** (commute hours).  
2. Weekends show slightly **higher bookings** than weekdays.  
3. Most rides are **short-to-mid distance (<25 km)**.  
4. **Digital payments dominate** over cash.  
5. **Customer cancellations > Driver cancellations**.  
6. Both **Driver & Customer Ratings** cluster around 4–5 stars.  
7. **Affordable vehicles (Sedan/Auto)** dominate bookings.  
8. **Off-peak hours** see low demand and driver underutilization.  

---

## Insights & Recommendations
- **Driver Allocation:** Increase availability during peak hours.  
- **Fare Optimization:** Adjust short-trip fares; promote longer rides.  
- **Digital Incentives:** Strengthen wallet/UPI offers.  
- **Reduce Cancellations:** Improve ETA accuracy & cancellation policies.  
- **Quality Control:** Use feedback loops for low ratings.  
- **Product Mix:** Focus on budget rides but market premium options.  
- **Off-Peak Incentives:** Discounts, driver bonuses, and subscription models.  

---

## Tech Stack
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 📈 Visualizations
- Histogram (Fare, Distance, Ratings)  
- Countplots (Day of Week, Vehicle Type, Payment Methods)  
- Scatterplot (Fare vs Distance)  
- Heatmap (Correlation, Hour vs Day Demand)  
- Pie & Donut Charts (Ride Status, Vehicle Type)  

---

##  Conclusion
Uber’s NCR ride data highlights a **commute-driven demand pattern**, strong **digital adoption**, and generally **positive service ratings**.  
However, **customer cancellations** and **off-peak underutilization** remain challenges.  
By implementing **dynamic allocation, optimized pricing, and targeted incentives**, Uber can significantly enhance **efficiency, customer satisfaction, and revenue growth**.  

---

## 📌 Author
Name: Vishnu N 
Email: vishnunandakumar.official@gmail.com 
GitHub: https://github.com/VishnuNandakumar/Uber-NCR-EDA 

---
