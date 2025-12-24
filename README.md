# 📊 Logistics Performance Analysis Using Excel Pivot Tables

## 📌 Project Overview
This project analyzes a logistics dataset to evaluate **shipment volume, route efficiency, delivery duration, delay patterns, supplier performance, customer trends, and material movement  using **Microsoft Excel Pivot Tables.
The objective is to identify operational inefficiencies and delay drivers and propose data-driven improvements for logistics performance.

## 📂 Dataset Summary
The dataset consists of logistics and transportation records, including booking details, routes, delivery duration, shipment type, suppliers, customers, and materials shipped.

**Key Statistics:**
* **3,582** distinct booking IDs
* **1,259** registered vehicles
* **1,235** drivers
* **36** customers
* Average transportation distance: **841 km**

---

## ❓ Problem Statements

This analysis was guided by the following questions:

1. What are the most frequently used shipment routes and their average distances?
2. Which routes experience the longest delivery durations?
3. When do shipment volumes peak?
4. What factors contribute to shipment delays?
5. Which suppliers handle the most shipments and experience higher delays?
6. Which customers receive the most shipments and how do delays vary across them?
7. What materials are shipped most frequently and how do delays differ by material type?
8. Where are the most common shipment delay bottlenecks?

---

## 🔍 Analysis Performed

Using Excel Pivot Tables, the following analyses were conducted:

* Route-based **trip frequency and average distance analysis**
* **On-time vs delayed** delivery comparison by shipment type
* **Supplier-level** shipment volume and delay analysis
* **Customer-level** shipment and delay distribution
* **Average delivery duration** analysis by route
* **Material movement** and delay analysis
* **Booking trends** by year and month

---

## 📈 Key Insights

### 🚛 Route & Distance Insights

* *Perumalpattu – Kottamedu Road (Oragadam Industrial Corridor)* recorded the **highest trip frequency (198 trips)** with an average distance of **557 km**, identifying it as a major logistics hub.
* Some routes showed **long average distances (2,000+ km)** but lower frequency, indicating long-haul shipments.

---

### ⏱️ Delivery Duration

* Routes in **Patna, Chhattisgarh, and Odisha** recorded the **longest average delivery durations**, exceeding **260,000 minutes**, suggesting distance-related or operational delays.

---

### 📅 Peak Shipment Periods

* Shipment activity increased significantly in **2020**, peaking between **June and August**.
* **August 2020** recorded the highest booking volume (**1,432 bookings**).

---

### 🚨 Delay Patterns

* **Market shipments** performed better with **81.03% on-time deliveries**.
* **Regular shipments** experienced higher delays, with **62.18% delayed**, indicating shipment-type inefficiencies.

---

### 🚚 Supplier Performance

* **Ekta Transport Company** handled the highest shipment volume (**238 bookings**) but also recorded a high number of delays.
* **VJ Logistics** demonstrated stronger on-time performance relative to shipment volume.

---

### 🧑‍🏭 Customer Insights

* **Larsen & Toubro Limited** recorded the highest number of shipments (**977**) and the highest delay count.
* **Daimler India Commercial Vehicles Pvt Ltd** had more on-time deliveries than delayed shipments.

---

### 📦 Material Movement

* **Auto Parts** were the most frequently shipped material (**1,212 shipments**).
* Materials such as **GRS Starter** and **Solenoid Assembly** showed relatively higher delays compared to shipment volume.

---

### 🛣️ Operational Bottlenecks

* Routes such as **Maraimalai Nagar** and **Chharodi, Gujarat** consistently recorded higher delay counts, identifying them as logistics bottlenecks.

---

## 💡 Recommendations

Based on the analysis, the following data-driven recommendations are proposed:

### 1️⃣ Prioritize High-Delay Routes

Routes with consistently high delays should undergo **route planning reviews**, including scheduling adjustments and improved dispatch coordination.

---

### 2️⃣ Re-evaluate Regular Shipment Processes

Given the high delay rate in Regular shipments, logistics managers should:

* Adjust delivery timelines
* Assign more reliable suppliers
* Implement stricter performance monitoring

---

### 3️⃣ Optimize Supplier Allocation

Suppliers with high delay counts should be:

* Reassigned from time-sensitive routes
* Closely monitored using delay-rate KPIs
* Balanced with better-performing suppliers such as VJ Logistics

---

### 4️⃣ Improve Service for High-Impact Customers

Customers experiencing frequent delays should receive:

* Customer-specific performance reviews
* Priority routing and supplier selection
* Proactive communication on delivery expectations

---

### 5️⃣ Material-Specific Planning

Materials with higher delay rates should be:

* Prioritized in scheduling
* Assigned to routes and suppliers with stronger on-time performance

---

## 🛠️ Tools Used

* **Microsoft Excel**

  * Pivot Tables
  * Distinct Count and Average aggregations
  * Filtering and sorting

---

## 🚀 Future Work

* Build predictive models for shipment delays
* Perform route optimization using geospatial analysis

---

## 📎 Author
**Olusesan Samuel**
 Data Analyst | Excel • SQL • Power BI
