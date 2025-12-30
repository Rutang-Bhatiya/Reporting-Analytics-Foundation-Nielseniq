# Reporting & Analytics Foundation – NielsenIQ  
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

![End-to-End Data Flow](visuals/data-flow-diagram.png)

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

![Product Hierarchy Example](visuals/product-hierarchy.png)

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

![Excel RTL Architecture](visuals/rtl-architecture.png)

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

![Sample Sales Trend](visuals/sample-sales-trend.png)

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

## 🔐 Data Confidentiality

All examples in this repository use **dummy data**.  
No proprietary NielsenIQ systems, schemas, or client data are exposed.
