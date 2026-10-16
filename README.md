# 📊 Data Intelligence & Customer Transaction Analytics Dashboard

An end-to-end Enterprise Data Analytics and Business Intelligence solution developed in **Microsoft Excel**. This project transforms 250+ raw customer transactional records into multi-layered strategic insights, dynamic financial simulations, predictive regression models, and an interactive executive dashboard.

---

## 📌 Table of Contents
- [🎯 Project Overview](#-project-overview)
- [✨ Key Technical Highlights](#-key-technical-highlights)
- [📂 Workbook Structure](#-workbook-structure)
- [🧠 Analytical Techniques & Implemented Concepts](#-analytical-techniques--implemented-concepts)
- [📊 Executive Dashboard & Visualizations](#-executive-dashboard--visualizations)
- [🔮 Scenario Manager & What-If Simulations](#-scenario-manager--what-if-simulations)
- [💡 Strategic Business Insights](#-strategic-business-insights)
- [🛠️ Tech Stack & Tooling](#️-tech-stack--tooling)
- [🚀 Getting Started](#-getting-started)

---

## 🎯 Project Overview

* **Dataset:** 250+ Multi-Category Transaction Records across 4 Geographical Territories
* **Domain:** E-Commerce, Retail Supply Chain & Consumer Behavioral Analytics
* **Core Objective:** Analyze transactional health, track customer tenure and customer lifetime value (LTV), identify high-value customer tiers, simulate revenue trajectories under variable market conditions, and deploy interactive visualization tools.

---

## ✨ Key Technical Highlights

* 📅 **Advanced Date & Temporal Engineering:** Calculation of customer tenure, dynamic month-end cycle closures, and live self-updating timestamps using iterative calculation logic.
* ⚡ **Dynamic Array Filtering:** Multi-criteria extraction isolating high-value order cohorts without manual filtering.
* 🎯 **Predictive Modeling & Statistical Forecasting:** What-If Scenario Analysis (Conservative, Base, Optimistic), Goal Seek target modeling, and Linear Regression utilizing the Data Analysis Toolpak.
* 👑 **RFM & Group-Level Customer Tiering:** Algorithmic ranking of customer lifetime spend classifying accounts into actionable segments (*VIP Tier 1*, *Core Tier 2*, *Standard Tier 3*).
* 🏷️ **Data Cleansing & String Manipulation:** Automated creation of standardized initials, abbreviations, and composite SKU Short Codes.
* 🎛️ **Synchronized Pivot & Slicer Architecture:** Interlinked visual reports cross-filterable by Product Category, Region, and Customer Tier.

---

## 📂 Workbook Structure

The workbook follows an organized multi-tier enterprise design:

| Sheet Tab | Purpose & Contents |
| :--- | :--- |
| **`Executive_Dashboard`** | High-level presentation layer featuring KPI summaries, interactive Pivot Charts, and multi-select Slicers. |
| **`Project Instructions`** | Complete business brief, grading criteria, and technical methodology specifications. |
| **`Final Project Dataset`** | Cleansed source data enriched with customer tenure, string abbreviations, tier tags, and simulation parameters. |
| **`Scenario Summary`** | What-If Scenario Manager report detailing Conservative, Base Case, and Optimistic financial projections. |

---

## 🧠 Analytical Techniques & Implemented Concepts

### 1️⃣ Date & Temporal Tracking
* **Dynamic Recency Engine:** Automated identification of current system date and live calculation updates.
* **Customer Tenure Metrics:** Calculated exact customer loyalty lifespans in years and months from initial onboarding.
* **Accounting Cycles:** Normalized variable transaction dates to precise month-ending balance periods for cyclical reconciliation.
* **Static Timestamping:** Configured iterative circular calculations to generate permanent order entry stamps upon transaction updates.

### 2️⃣ Dynamic Array Filtering & List Matching
* **Multi-Value Condition Filter:** Extracted targeted high-ticket purchase records directly into dedicated analysis blocks.
* **Dual-List Reconciliation:** Automated matching between distinct customer rosters to instantly isolate repeating buyers and eliminate duplicates.
* **Frequency Detection:** Algorithmic identification of the most frequently sold product catalog items and top repeat customer profiles.

### 3️⃣ Text Parsing & String Transformation
* **Customer Initials & Monograms:** Concatenated sub-string extractions converting full customer names into compact abbreviations (e.g., `Paul Baker` ➔ `PB`).
* **Product Short Codes:** Standardized internal catalog indexing combining product prefixes with unique identifier IDs (e.g., `MON-P009`).

### 4️⃣ Customer Lifetime Value & Tiering
* **Group-Level Aggregation:** Summarized total spend on an individual account level across the full transaction log.
* **Tier Categorization:** Multi-condition threshold rules classifying customer revenue bands into *Tier 1 - VIP*, *Tier 2 - Growth*, and *Tier 3 - Standard*.

---

## 🔮 Scenario Manager & What-If Simulations

To support strategic forecasting, multiple pricing and demand conditions were modeled:

| Scenario | Price Adjustment Factor | Volume Growth Factor | Business Objective |
| :--- | :---: | :---: | :--- |
| **Conservative** | 0.95 (-5%) | 0.90 (-10%) | Defensive stress test against market downturns and supply constraints. |
| **Base Case** | 1
