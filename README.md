# 🚆 UK Train Revenue & Performance Analysis

### Data Analytics Case Study (Power BI)

## 📌 Problem Statement

UK railway operations generate high revenue, but profitability is impacted by:

* Heavy discounting strategies
* Delays and cancellations
* Uneven route performance

The objective was to **identify revenue leakages, optimize pricing, and improve operational efficiency** using data.

---

## 🎯 Objectives

* Analyze revenue trends across months and ticket types
* Identify high and low performing routes
* Measure impact of delays and cancellations
* Quantify revenue loss due to discounts and refunds

---

## 📊 Dataset

* Passenger journeys (~31K records)
* Ticket types: Advance, Anytime, Off-Peak
* Route-level data (stations, segments)
* Delay, cancellation, and refund data

---

## 🛠 Approach

### 1. Data Preparation

* Cleaned missing and inconsistent values
* Standardized route and station naming
* Created calculated fields
  
---

### 2. Data Modeling

* Built relationships across:

  * Routes
  * Ticket types
  * Time (monthly trends)
* Optimized model for fast dashboard interaction

---

### 3. Visualization Design

Built a multi-page Power BI dashboard:

* Revenue Analysis
* Route Performance
* Railway Operations
* Passenger Usage

---

## 🔍 Key Findings

### 💰 Revenue Leakage is the Biggest Problem

* Gross Revenue: **£742K**
* Net Revenue: **£703K**
* Discounts: **£625K**
* Refunds: **£39K**

👉 Discounts are the primary issue, not refunds.

---

### 🎟 Ticket Strategy is Flawed

* Advance tickets dominate volume (~62%)
* Lowest revenue per trip

👉 High usage but poor profitability.

---

### 🚉 Route-Level Insights

* Best route:

  * London Kings Cross → York (**highest revenue per trip**)

* Worst tradeoff:

  * Manchester → Liverpool (**high demand, low revenue**)

* Critical risk:

  * Edinburgh → London (**0% reliability**)

---

### ⏱ Operational Performance

* Reliability: **86.82%**

* Refund Rate: **5.22%**

* Major causes:

  * Signal failures
  * Weather
  * Staff shortages

* Highest cancellation route:

  * Liverpool → Birmingham (**14.29%**)

---

### 📉 Delays Drive Refunds

* Delayed journeys: **2.29K**
* Cancelled journeys: **1.88K**

👉 Strong correlation between delays and refunds.

---

## 💡 Business Recommendations

### 1. Fix Pricing Strategy

* Reduce excessive reliance on Advance tickets
* Introduce dynamic pricing for high-demand routes

---

### 2. Optimize Routes

* Increase prices on:

  * Manchester → Liverpool
* Improve reliability on:

  * Edinburgh → London

---

### 3. Reduce Revenue Leakage

* Rebalance discount structure
* Target high-margin ticket mixes

---

### 4. Improve Operations

* Address root causes:

  * Signal failures
  * Staffing gaps
* Prioritize high-revenue routes for reliability improvements

---

## 📈 Impact (What This Enables)

* Higher profit margins without increasing passenger volume
* Better pricing decisions using data
* Reduced operational inefficiencies
* Improved customer satisfaction

---

## 🧠 What I Learned

* Revenue problems are often pricing problems, not demand problems
* Aggregated metrics hide route-level inefficiencies
* Visualization design directly affects decision-making clarity

---

## 🛠 Tools Used

* Power BI (Dashboarding, DAX, Data Modeling)

---
