


# Pharmacy Operations Performance Analysis (2025)

## Project Overview

An in-depth analysis of pharmacy supply chain and service performance across two centres using operational data from **January – November 2025**.
This project evaluates **drug requisition efficiency**, **supplier performance**, **order fulfillment**, and **patient satisfaction**, identifying bottlenecks that impact service delivery.



##  Business Objectives

* Measure Drug Requisition Turnaround Time (TAT)
* Evaluate supplier delivery performance
* Track order fulfillment and prescription fill rates
* Identify drugs and vendors causing delays
* Assess overall patient satisfaction



##  Dataset

The dataset contains **anonymized pharmacy operational data** from an **Active Hospital Setup**, including:

* **Columns:** `InvestigationName`, `Results_Received_TAT_Min`, `Purchase_Order_TAT`, `GRN_Approval_TAT`, `Prescription_Fill_Rate`, `Overall_Satisfaction_Score`, `SupplierName`
* **Period:** January – November 2025
* **Rows:** Several thousand transactions across two pharmacy centres
* **Privacy:** All personal identifiers removed; patient-level data anonymized



##  Analysis & Findings

###  Centre 1 Pharmacy (Feb – Nov 2025)

**Key Metrics**

* Number of Suppliers: **33**
* Median Drug Requisition TAT: **3 days**
* Average Drug Requisition TAT: **5 days**
* Purchase Order Approval TAT: **7 hours**
* GRN Approval TAT: **15 minutes**
* Order Fulfillment Rate: **88%**
* Prescription Fill Rate: **93.71%**
* Overall Satisfaction Score: **97%**

**Findings**

* Internal procurement workflows are highly efficient, with rapid PO and GRN approvals.
* The gap between median (3 days) and average (5 days) TAT highlights **occasional supplier-driven delays**.
* Monthly requisition TAT remains stable, indicating predictable procurement performance.
* A small number of vendors contribute disproportionately to extreme delays (>40–55 days).
* Critical drugs such as **Sitagliptin** and **Artesunate** occasionally experience prolonged requisition timelines.

**Risk Areas**

* Dependence on underperforming suppliers
* Long delays for essential medications



### Centre 2 Pharmacy (Jan – Nov 2025)

**Key Metrics**

* Number of Suppliers: **51**
* Median Drug Requisition TAT: **6 days**
* Average Drug Requisition TAT: **10 days**
* Order Fulfillment Rate: **90%**
* Prescription Fill Rate: **90%**
* Overall Satisfaction Score: **86%**

**Findings**

* A larger supplier base increases operational complexity and variability.
* The difference between median and average TAT indicates **significant vendor performance inconsistencies**.
* Certain drugs experience extreme requisition delays ranging from **40 to 94 days**.
* Monthly requisition TAT fluctuates between **5–8 days**, reflecting inconsistent supplier reliability.
* Reduced fill rates correlate with lower patient satisfaction.

---

##  Comparative Insights (Centre 1 vs Centre 2)

| Metric                  | Centre 1 | Centre 2 |
| ----------------------- | -------- | -------- |
| Median Requisition TAT  | 3 days   | 6 days   |
| Average Requisition TAT | 5 days   | 10 days  |
| Order Fulfillment Rate  | 88%      | 90%      |
| Prescription Fill Rate  | 93.71%   | 90%      |
| Satisfaction Score      | 97%      | 86%      |

**Interpretation**

* Centre 1 outperforms Centre 2 in speed, consistency, and patient satisfaction.
* Supplier performance, rather than internal processes, is the main driver of delays.
* Larger supplier networks increase risk unless closely monitored and optimized.



## Dashboard & Visualizations

## Centre 1 Dashboard Preview

![Centre 1 Dashboard Preview](images/Centre%201%20dashboard_preview.png%20%20\(1\).png)

**Key Insights**

* Strong internal efficiency with minimal approval delays.
* Outlier suppliers significantly inflate average TAT.
* High prescription fill rates support excellent patient satisfaction.



## Centre 1 Dashboard Preview

![Centre 2 Dashboard Preview](images/Centre%202%20%20dashboard_preview.png%20(1).png)


**Key Insights**

* Supplier variability drives extended requisition delays.
* High-risk drugs require closer procurement monitoring.
* Operational delays negatively impact patient experience.



##  Business Recommendations

* **Supplier Performance Management:** Introduce SLAs with penalties for late deliveries.
* **Critical Drug Monitoring:** Flag high-risk drugs for proactive procurement planning.
* **Vendor Consolidation:** Reduce supplier base to high-performing vendors.
* **Early Warning Dashboards:** Automate alerts for drugs exceeding TAT thresholds.
* **Cross-Centre Best Practices:** Apply Centre 1 operational practices to Centre 2.



##  Skills & Tools Used

* **Tools:** Power BI, DAX, Excel, GitHub
* **Skills:** Data cleaning, KPI analysis, supplier performance analysis, TAT monitoring, dashboard design, portfolio documentation



##  Disclaimer

All data used in this project is fully anonymized. No patient-identifiable information is included.



###  Final Note

This project demonstrates **data-driven operational analysis**, combining **business insight, healthcare context, and visualization** to support decision-making.


