### Data Engineering Pipeline for Supply Chain Mitigation & Revenue Protection

## Problem Statement

To prevent platform churn driven by third-party delivery delays across Brazil, this project engineers an optimized data engine that maps regional supply chain vulnerabilities, isolates financial Capital-at-Risk, and establishes data-driven, state-specific SLA frameworks.

## 📂 Project Architecture & Deliverables

* **`delay_calculation.ipynb`**
The core development environment where the hybrid analytical pipeline was architected. It leverages **DuckDB** for in-memory OLAP operations to execute rapid relational joins on multi-source datasets, implements vectorized epoch math for temporal feature engineering (`total_delivery_time_days`), and applies conditional logical categorization to bucket deliveries into key operational states.
* **`delay_calc_sample_1000.csv`**
A production-ready data output slice containing a statistically representative sample of 1,000 randomized records. This dataset unifies transactional metrics, geographic tracking attributes, and calculated delivery statuses—designed to validate pipeline logic under local hardware constraints and seamlessly fuel downstream Tableau visualizations and executive risk reporting.


## 🛠️ Technical Achievements & Strategic Impact

* **High-Speed In-Memory OLAP:** Eliminated heavy database server overhead by utilizing DuckDB to blend high-density geospatial points with fragmented transactional datasets instantly.
* **Targeted Freight Sourcing:** Generates structured geographic breakdowns that expose regional delivery bottlenecks, enabling management to allocate capital precisely toward high-velocity carrier partnerships.
* **Revenue Protection:** Connects order prices directly to delayed pipelines, quantifying the exact Gross Merchandise Value (GMV) exposed to supply chain friction.
* **Proactive Retention:** Powers automated customer experience (CX) workflows by isolating "Not Delivered Yet" milestones, allowing Olist to mitigate consumer friction before it degrades Customer Lifetime Value (CLV).
