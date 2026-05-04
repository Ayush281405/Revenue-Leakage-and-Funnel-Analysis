#  Revenue Leakage & Funnel Analysis (Power BI + SQL)

##  Project Overview

Most businesses track revenue, orders, and delivery metrics.
But very few understand:

> **Where revenue is actually being lost.**

This project analyzes an e-commerce dataset to identify:

* Revenue leakage across the funnel
* Operational inefficiencies in delivery
* Geographic and category-level performance gaps

Instead of reporting metrics, this project focuses on:

> **Diagnosing where value is being destroyed**

---

##  Problem Statement

Organizations often assume:

* High order volume = strong performance
* High revenue = healthy business

But in reality:

* Revenue can leak through cancellations, delays, and inefficiencies
* Operational issues silently reduce profitability
* Growth can mask structural problems

This project answers:

* Where is revenue leaking?
* What causes delivery inefficiencies?
* Which regions and categories drive or destroy value?

---

##  Tools & Technologies

* **SQL**

  * Data extraction
  * Data cleaning & transformation
  * Aggregations and joins across multiple tables

* **Power BI**

  * Data modeling
  * DAX measures
  * Interactive dashboard design

---

## Dashboard Overview

### 1. Executive Summary

![Executive Summary](assets/executive-summary.png)

Key KPIs:

* Total GMV: 50.95M
* Total Revenue: 49.53M
* Revenue Leakage: 2.78%
* Total Orders: 92.2K
* Delivery Rate: 98%
* AOV: $533

Insight:

> Strong topline metrics, but hidden leakage reduces real value.

---

### 2. Delivery & Operations Analysis

![Delivery Ops](assets/delivery-ops.png)

Key Metrics:

* On-Time Delivery: 92.05%
* Late Deliveries: 7.95%
* Avg Delivery Time: 12.8 days

 Insights:

* Delivery delays directly impact customer satisfaction
* Certain states show significantly higher delay rates
* Operational inefficiencies are not evenly distributed

---

### 3. Revenue Leakage & Risk Analysis

![Revenue Risk](assets/revenue-risk.png)

Key Metrics:

* Cancellation Rate: 0.47%
* Revenue Leaked: 1.42M
* Fulfillment Failures: 602

Insights:

* Specific product categories contribute disproportionately to cancellations
* Revenue leakage shows temporal spikes → indicates instability
* Leakage is not random — it is **pattern-driven**

---

### 4. Categories & Geographic Analysis

![Categories Geo](assets/categories-geo.png)

Key Metrics:

* Top Category: Health & Beauty ($4.46M)
* Top City: Sao Paulo ($6.82M)
* Top State: SP ($18.72M)

 Insights:

* Revenue is highly concentrated in specific regions
* Category performance varies significantly
* Logistics and geography influence revenue realization

---

## Key Business Insights

* **Revenue leakage is structural, not accidental**
  It consistently appears in specific categories and time periods

* **Delivery performance impacts revenue realization**
  Delays increase cancellations and reduce customer trust

* **Revenue concentration increases risk**
  Over-dependence on specific regions limits scalability

* **High performance metrics can be misleading**
  Strong revenue numbers can hide operational inefficiencies

---

## Project Structure

```id="3ldm92"
Revenue-Leakage-Analysis/
│
├── assets/                # Dashboard images
├── dataset/               # Raw & cleaned data
├── sql/                   # SQL queries
├── powerbi/               # .pbix file
└── README.md
```

---

##  How to Use

1. Clone the repository
2. Open SQL scripts to understand data preparation
3. Load dataset into Power BI
4. Open `.pbix` file
5. Explore dashboards using filters and slicers

---

##  Conclusion

This project demonstrates that:

> **Revenue growth alone does not indicate business health.**

True performance requires understanding:

* Where revenue is lost
* Why inefficiencies occur
* How operations impact profitability

---

## 🔗 Future Improvements

* Add predictive modeling for revenue leakage
* Build anomaly detection for delivery delays
* Integrate real-time data pipelines
* Expand analysis across multiple time periods

---

##  Author

**Ayush Kaushik**
Aspiring Data Analyst | AI Engineer

---
