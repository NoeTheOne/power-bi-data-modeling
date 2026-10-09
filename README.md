# Power BI Data Modeling Project

This project walks through turning a messy 23-table dataset into a clean Power BI star schema model that can be used reliably for reporting and analytics.

## Project Goal
The objective is to transform a complicated dataset containing 23 interconnected tables into a well-structured star schema. This involves identifying business entities, separating facts from dimensions, creating relationships, building measures, and validating the final model.

## Phases
1. **Prepare & Explore** (Step 1)
2. **Create Dimensions** (Steps 2 – 4)
3. **Create the Facts** (Steps 5 – 8)
4. **Polish** (Steps 9 – 12)

## Rules
1. **Build a Star Schema:** A fact in the middle, dimensions around it.
2. **Understand before making any changes:** Always read the grain first.
3. **Every column earns its place:** If a column doesn’t help the report, drop it.
4. **Protect the numbers:** Be aware of the Totals, re-check after every change.

## Standards
* **Language:** English
* **Naming:** `snake_case`
* **Tables (prefix):** `fact_` & `dim_`
* **Keys (suffix):** `_id` (From source) & `_key` (Created by us in PBI)
* **Friendly column names:** `customer_name`, `total_revenue`, `order_status`
