# ✈️ Airline Route Investment & Profitability Analytics

## 📌 Project Overview

This project evaluates U.S. domestic airline routes to identify attractive opportunities for market entry. The analysis combines route demand, profitability, operating costs, occupancy, and delay performance to determine which round-trip routes offer the strongest investment potential.

The project demonstrates an end-to-end data analytics workflow including **data cleaning, exploratory analysis, KPI development, profitability analysis, route scoring, breakeven analysis, and data visualization**.

> **Note:** This repository does not contain any proprietary datasets, assessment instructions, or confidential source materials. It contains only portfolio-level documentation and materials appropriate for public sharing.

---

## 🎯 Business Objective

The analysis focuses on answering several key business questions:

* Which domestic round-trip routes have the highest passenger demand?
* Which routes generate the strongest estimated profitability?
* How do occupancy, operating costs, and delays affect route performance?
* Which routes provide the strongest combination of profitability and operational reliability?
* How quickly could the required aircraft investment be recovered?
* Which KPIs should be monitored after entering a new route?

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Jupyter Notebook**
* **Tableau**
* **Data Cleaning & Transformation**
* **Exploratory Data Analysis (EDA)**
* **KPI & Profitability Analysis**

---

## 🔍 Analytical Approach

### 1. Data Preparation

Prepared and validated flight, ticket, and airport-level information for analysis by:

* Handling missing and inconsistent values
* Identifying and treating outliers
* Removing cancelled flights where appropriate
* Standardizing airport and route information
* Creating round-trip route identifiers
* Combining relevant information into analysis-ready datasets

### 2. Exploratory Data Analysis

Analyzed route performance across:

* Flight volume
* Passenger occupancy
* Ticket revenue
* Operating costs
* Delay performance
* Route profitability

The analysis covered **2,700+ U.S. domestic round-trip routes**.

### 3. Route Profitability Analysis

Developed route-level financial metrics to compare:

**Revenue − Operating Costs = Estimated Route Profit**

Revenue and cost components were evaluated at the route level to identify routes with attractive financial performance.

### 4. Route Selection

Compared routes using multiple business and operational indicators rather than profitability alone.

Key considerations included:

* Profitability
* Flight demand
* Occupancy
* Operating costs
* Delay performance
* Operational reliability

The analysis ultimately identified **5 high-potential routes** for market-entry consideration.

---

## 💰 Investment & Breakeven Analysis

Performed route-level breakeven analysis against a modeled total aircraft investment of **$450 million**.

The analysis estimated how many round trips would be required for each recommended route to recover its allocated aircraft investment based on expected route profitability.

> All financial results represent modeled estimates based on project assumptions and should not be interpreted as realized financial returns.

---

## 📊 Tableau Visualization

Developed Tableau visualizations to communicate:

* Route profitability
* Flight volume
* Occupancy
* Delay performance
* Route comparisons
* Investment considerations

The visual analysis supports comparison of financial and operational performance across potential routes.

---

## 📈 Recommended KPIs

Key metrics for ongoing route monitoring include:

* **Profit per Round Trip**
* **Total Route Profit**
* **Occupancy Rate**
* **Flight Volume**
* **Revenue per Trip**
* **Operating Cost per Trip**
* **Departure Delay**
* **Arrival Delay**
* **On-Time Performance**
* **Breakeven Progress**

---

## 💡 Key Takeaways

* Analyzed **2,700+ round-trip routes** using financial and operational performance indicators.
* Identified **5 routes** with strong market-entry potential.
* Evaluated route attractiveness using profitability, occupancy, demand, cost, and delay performance.
* Performed breakeven analysis against a modeled **$450M aircraft investment**.
* Developed Tableau visualizations and KPIs to support data-driven route investment decisions.

---

## 🔮 Future Improvements

Potential extensions of the analysis include:

* Incorporating multiple quarters or years of historical data
* Evaluating seasonal changes in passenger demand and pricing
* Incorporating fuel-price fluctuations
* Analyzing competitive airline presence by route
* Incorporating aircraft utilization and capacity constraints
* Developing forecasting models for route demand and profitability
* Creating automated data pipelines and dashboard refreshes

---

## 👤 Author

**Sanjay Narra**

Data Analyst | SQL | Python | Power BI | Tableau
