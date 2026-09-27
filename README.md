# 🚕 Cab Booking & Ride Analytics — Exploratory Data Analysis

## 📌 Project Overview

This project focuses on analyzing cab booking data using Python and Exploratory Data Analysis (EDA).

The analysis combines multiple datasets to understand customer behavior, driver performance, ride patterns, revenue generation, payment trends, and ride-related incidents.

The project follows an end-to-end data analysis workflow including data cleaning, data integration, feature engineering, KPI calculation, visualization, and business insight generation.

---

## 🎯 Project Objectives

- Clean and preprocess raw cab booking datasets
- Merge multiple datasets into a unified analytical dataset
- Handle missing values and duplicate records
- Standardize inconsistent data
- Perform feature engineering
- Calculate business KPIs
- Analyze ride performance and customer behavior
- Analyze driver efficiency and revenue trends
- Create visualizations for business reporting

---

## 📂 Datasets

The project consists of five datasets:

| Dataset | Description |
|---|---|
| Customers | Customer details including demographic information |
| Drivers | Driver details such as experience and ratings |
| Orders | Ride booking information including fare, payment mode, dates, and service type |
| Companies | Cab company information |
| Incidents | Ride-related incidents and associated fines |

---

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Filled missing Order Date values using Forward Fill
- Removed rows with missing Customer IDs where required
- Corrected inconsistent data types
- Converted date columns into datetime format
- Standardized categorical values
- Removed unnecessary spaces and formatting issues
- Verified unique values
- Performed data consistency checks

---

## 🔗 Data Integration

Multiple datasets were merged using common keys to create a single analytical dataset.

The integrated datasets include:

- Customers
- Drivers
- Orders
- Companies
- Incidents

---

## ⚙️ Feature Engineering

The following features were created for further analysis:

- Month
- Age Category
- Fine Status

---

## 📊 Business KPIs

The project calculates the following KPIs:

- Total Revenue
- Total Orders
- Total Customers
- Total Drivers
- Total Companies
- Total Distance Travelled
- Average Fare per Ride
- Total Driver Tips
- Average Customer Rating
- Total Fine Amount
- Total Incidents
- Average Driver Experience
- Repeat Customer Rate
- Incident Rate
- Revenue by City
- Most Popular Service Type
- Most Used Payment Method
- Highest Rated Driver
- Highest Revenue Generating Company
- Average Customer Age
- Percentage of Ratings Above 4★

---

## 📈 Exploratory Data Analysis

The following visualizations were created:

- Revenue by Pickup City
- Ride Distribution by Service Type
- Payment Mode Distribution
- Ride Fare Distribution
- Distance vs Ride Price Analysis
- Ride Distance Distribution
- Revenue Trend over Time
- Ride Fare Outlier Analysis
- Customer Gender Distribution
- Revenue by Cab Company
- Driver Count by Cab Company
- Revenue vs Fine Contribution
- Fine Amount by Incident Type
- Customer Distribution by Age Category

---

## 🔍 Key Findings

- Total revenue generated was approximately **₹7,39,633**.
- A total of **4,922 rides** were completed.
- The platform served **2,438 unique customers**.
- There were **500 registered drivers** and **10 cab companies**.
- Drivers collectively covered **42,831 km**.
- The average base fare per ride was **₹43**.
- Drivers received **₹52,937** in customer tips.
- Average customer rating was **3★**.
- A total of **420 incidents** were reported.
- Total fines amounted to approximately **₹4,83,129**.
- **Sedan** was the most preferred service type.
- Average driver experience was **6 years**.
- Average customer age was **33 years**.
- The platform operated across **17 cities**.
- **Net Banking** was the most frequently used payment method.
- **Rapido** received the highest number of ride bookings.
- **41%** of rides received ratings of 4★ or higher.
- The overall **incident rate was 9%**.
- **58%** of customers booked more than one ride.
- Driver **DRVO235** had the highest average rating of **4.7★**.
- **Rapido** generated the highest revenue of approximately **₹95,331**.
- **Chandigarh** had the highest customer base with **199 customers**.
- **Mumbai** had the highest number of drivers with **41 drivers**.

---

## 📁 Project Structure

```text
Cab-Exploratory-Data-Analysis/
│
├── README.md
│
├── Cab_Exploratory_Data_Analysis.ipynb
│
├── Data/
│   ├── customers.csv
│   ├── drivers.csv
│   ├── orders.csv
│   ├── companies.csv
│   └── incidents.csv
│
└── Report/
    └── Cab_Exploratory_Data_Analysis.pdf
