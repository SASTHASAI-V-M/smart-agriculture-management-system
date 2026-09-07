# Smart Agriculture Management System 🌾

An end-to-end relational database solution built with MySQL to streamline agricultural operations, manage supply chains, and analyze sales performance.

---

## 📌 Project Overview
The **Smart Agriculture Management System** digitizes data flow across farming operations. It tracks entities including farmers, lands, crops, agricultural seasons, suppliers, harvesting output, regional market prices, and sales records.

### Key Objectives
- **Centralized Management:** Integrates multi-entity operations under unified Primary/Foreign Key constraints.
- **Data Integrity:** Enforces relational rules, domain check constraints, and indexed relationships across 9 core tables.
- **Analytical Insights:** Leverages views and aggregate queries to evaluate market dynamics, total yield, and estimated profitability.

---

## 🛠️ Database Design & Tech Stack
- **Database Engine:** MySQL
- **Tooling:** MySQL Workbench / DBeaver
- **Schema Architecture:** 9 Tables (Farmer, Land, Crop, Season, Supplier, Production, Market, Market_Price, Sales)
- **Key Concepts:** DDL, DML, DQL, Multi-table JOINs, GROUP BY & HAVING aggregations, Database Views, Indexes, Constraints

---

## 📊 Core Functionality
- **Data Definition (DDL):** Formatted table structures with AUTO_INCREMENT IDs, UNIQUE keys, and custom CHECK constraints.
- **Data Analysis & Views:** Pre-configured analytical queries and custom views:
  - `vw_farmer_performance`
  - `vw_crop_performance`
  - `vw_market_performance`
  - `vw_supplier_performance`
  - `vw_state_summary`

---

## 🚀 How to Run the Queries
1. Clone this repository or download the `.sql` script.
2. Open **MySQL Workbench** or **DBeaver**.
3. Execute the table creation statements to construct the schema.
4. Run the analytical query suite to query performance data.
