#  Airline Passenger Satisfaction Analysis

##  Project Overview

This project analyzes airline passenger data to identify key factors influencing **customer satisfaction**.
Using exploratory data analysis (EDA), feature engineering, and visualization techniques, we derive **actionable business insights** to improve service quality and operational efficiency.

---

## Dataset Summary

* **Total Records:** 129,487
* **Key Features:**

  * Demographics (Age, Gender)
  * Travel Details (Class, Distance, Type)
  * Service Ratings (Wi-Fi, Comfort, Cleanliness, etc.)
  * Operational Metrics (Delays)
* **Target Variable:** `Satisfaction`

---

##  Key Feature Engineering

* Created **`Average_ServiceRating`** from all service-related columns
* Engineered **`Total Delay`** = Departure Delay + Arrival Delay
* Segmented passengers into **Age Groups**

---

##  Key Insights & Business Recommendations

---

###  1. Digital Experience & Connectivity Overhaul

**Insight:** Digital services are the primary drivers of dissatisfaction.

* **In-flight Wi-Fi:** Mean = **2.73 / 5** (lowest-rated feature)
* **Ease of Online Booking:** Mean = **2.75**
* **Gate Location:** Mean = **2.97**

**Recommendations:**

* Invest in **high-speed Wi-Fi infrastructure**
* Improve **mobile app UI/UX**
* Enhance **airport navigation systems**

---

###  2. Operational Efficiency & Delay Management

**Insight:** Arrival delays have a stronger negative impact than departure delays.

**Recommendations:**

* Optimize **flight paths**
* Improve **ground handling efficiency**
* Provide **real-time delay updates (SMS/notifications)**

---

###  3. Strategic Service Optimization by Travel Class

**Insight:**

* Business Class satisfaction is **high for long-haul flights**
* Drops significantly for **short-haul routes**

**Recommendations:**

* Focus on **efficiency perks** for short-haul Business Class:

  * Priority boarding
  * Lounge access
  * Fast-track security

---

###  4. Leveraging High-Performing Services

**Top-rated services:**

* **In-flight Service:** 3.64
* **Baggage Handling:** 3.63

**Recommendations:**

* Maintain consistency in these areas
* Use them as **core brand strengths**

**Target Audience Insight:**

* Average passenger age ≈ **39 years**
* Focus on **Adult segment**, expand strategies for Youth & Seniors

---

###  5. Data-Driven Satisfaction Summary

* **Average Total Delay:** ~30 minutes

  * Departure: 14.6 min
  * Arrival: 15.1 min

**Insight:**
Reducing delays is key to shifting passengers from
 *Neutral/Dissatisfied → Satisfied*

**Physical Comfort Analysis:**

* Seat Comfort: 3.44
* Cleanliness: 3.29

 Indicates physical services are stable, but **functional/digital services need improvement**

---

##  Visualizations

The project includes:

* Distribution plots (Age, Delays)
* Service rating comparisons
* Satisfaction vs key features
* Feature-engineered insights

---

##  Tech Stack

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Jupyter Notebook**

---

##  Conclusion

This analysis highlights that **digital experience, delay management, and service optimization** are the most critical drivers of customer satisfaction.

Focusing on these areas can significantly improve **customer retention, brand perception, and overall profitability**.

---

##  Future Improvements

* Build a **machine learning model** to predict satisfaction
* Deploy an **interactive dashboard (Tableau/Power BI)**
* Implement **real-time analytics pipeline**

---
