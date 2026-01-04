**Enterprise Reporting, Automation & SQL-Based Analytics Concepts**

---

## 1️⃣ Background

This repository represents the **foundation phase of my analytics career at NielsenIQ**, where I worked as a **Reporting Analyst** supporting enterprise FMCG clients.

The work focused on:

- SQL-based analytical concepts via **Answers**
- Large-scale reporting automation using **Advanced Excel (RTL templates)**
- Business analysis, visualization, and customer enablement

All examples in this repository use **dummy data** to respect confidentiality.

---

## 2️⃣ Scope & Scale

- Managed approximately **1000 recurring analytical reports**
- Markets covered: **Switzerland & Austria**
- Supported FMCG clients across multiple categories and product hierarchies
- Ensured **accuracy, consistency, and on-time delivery** at enterprise scale

This role required strong discipline, automation, and a deep understanding of business logic.

---

## 📊 End-to-End Data Flow

![End-to-End Data Flow]

*High-level flow from SQL-based extraction to business insights.*

---

## 1.1 Answers – SQL-Based Analytics Concepts

Answers functioned as a **SQL-driven analytics layer**, where business selections were translated into structured query logic.

Although users interacted via a UI, the underlying concepts mirrored SQL behavior:
- Filtering
- Aggregation
- Grouping
- Parameter-driven queries

The output of Answers was always a **raw data extract**, not a formatted report.

---

## 1.2 Dynamic Selection Logic (Answers)

### Market, Product, Fact & Time Selections

Report creation was driven by structured selections that controlled the raw data extract.

![Product Hierarchy Example]

*Illustrative product hierarchy used for aggregation and roll-ups.*

**Market Selection**
- Total Market
- Coop
- Migros

**Product Selection**
- Single products
- Multi-level hierarchies
- Custom dynamic hierarchies (thousands of items)

**Fact Selection**
- Sales Value
- Volume
- Price
- Market Share

**Time Selection**
- YTD, MAT
- Month, Year, Week
- 4-4-4 and 4-4-5 calendars

---

## 1.3 Excel RTL Framework & Automation

![Excel RTL Architecture]

*Conceptual view of the Excel RTL reporting framework.*

The raw output from Answers was fed into **Advanced Excel RTL templates**.

**Key characteristics**
- Hundreds of sheets per file
- One visible reporting layer
- Hidden calculation and control layers

**Automation Flow**
1. Raw data refresh
2. RTL recalculation
3. KPI update
4. Visual refresh

---

## 1.4 Analysis & Visualization

![Sample Sales Trend]

*Example sales trend visualization using dummy data.*

### Analysis Performed
- Trend analysis
- Period comparison
- Market share evaluation
- KPI variance analysis

Visuals were designed to answer **business questions**, not just display data.

---

## 1.5 Customer Enablement & Schema Explanation

Customers were supported in understanding:
- Database schemas
- Product hierarchies
- KPI definitions

This enabled:
- Self-service reporting
- Correct interpretation of outputs
- Reduced operational dependency

---

## How This Repository Fits in the Bigger Journey

This repository represents **Phase 1**

- **Phase 1:** Reporting & Analytics Foundation [`Nielseniq-reporting-analytics-foundation (this repo)`](https://rutang-bhatiya.github.io/1.0-Reporting-Analytics-Foundation-Nielseniq/) 
- **Phase 2:** BI Transformation & Data Lake Migration [`Nielseniq-bi-transformation-discover`](https://rutang-bhatiya.github.io/2.0-BI-Transformation-Data-Lake-Migration-NielsenIQ/){:target="_blank"}
- **Phase 3:** Database Architecture & Business Translation [`Nielseniq-database-architecture-business-translation`](https://rutang-bhatiya.github.io/3.0-Database-Architecture-Customer-Enablement/){:target="_blank"}

Each phase is documented separately for clarity and focus.

---
## 🔐 Data Confidentiality

All examples in this repository use **dummy data**.  
No proprietary NielsenIQ systems, schemas, or client data are exposed.

---

## Navigation

- **Overview:** [`About Me`](https://rutang-bhatiya.github.io/Rutang-Bhatiya/){:target="_blank"}
  *It contain links to My portfolio and all major pages and projects*

- **NielsenIQ:** [`NielsenIQ-Enterprise-Analytics-Journey`](https://rutang-bhatiya.github.io/Enterprise-Analytics-Journey-NielsenIQ/){:target="_blank"}
  *Links to all Nielsen Repo*

- **ECO3:** [`ECO3-enterprise-analytics-journey`](https://rutang-bhatiya.github.io/ECO3-enterprise-analytics-journey/){:target="_blank"}
  *Links to all ECO3 Repo*
