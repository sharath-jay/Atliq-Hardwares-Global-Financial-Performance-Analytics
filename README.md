# Atliq-Hardwares-Global-Financial-Performance-Analytics

**Project Overview**

This project focuses on transforming raw transactional data into actionable financial insights for Atliq Hardwares, a global electronics manufacturer. Using Excel (Power Query & Power Pivot), I developed a robust data model to analyze Profit and Loss (P&L) statements across 27+ international markets.

The primary objective was to empower stakeholders to evaluate annual profitability and monitor quarterly trends, enabling data-driven decisions regarding market expansion and margin optimization.

**Technical Skills & Workflow**

The project follows the ETL (Extract, Transform, Load) methodology to ensure data integrity and scalability:

1. Data Extraction & Transformation: Utilized Power Query to clean and shape raw data, including the generation of a custom Date Table to support non-standard fiscal years.
2. Data Modeling: Established a Star Schema using Power Pivot, managing relationships between sales, products, and geography tables.
3. Time Intelligence: Derived fiscal months and quarters to enable year-over-year (YoY) and quarterly trend analysis.
4. DAX (Data Analysis Expressions): Created calculated columns and measures to quantify key performance indicators (KPIs).

**Key Financial Metrics**

The analysis focuses on four critical metrics to evaluate market health:
1. Net Sales - Total revenue generated (USD Millions).
2. COGS - Direct costs associated with goods sold.
3. Gross Margin - Absolute profit ($) before operating expenses.
4. GM % - Profitability efficiency as a percentage of Net Sales.

**Performance Insights (FY 2021)**

Volume Leader: India recorded the highest Net Sales at $161.26M with a 32.0% Gross Margin.

Efficiency Leader: New Zealand achieved the highest margin efficiency with a 48.2% GM%, despite lower total volume ($11.40M).

**Project Impact**

By integrating supplementary datasets into a centralized data model, this tool allows management to:

1. Identify Profit Drivers: Quickly isolate high-performing markets vs. those with margin leakage.
2. Monitor Efficiency: Analyze the relationship between sales volume and production costs.
3. Scalability: The model is designed to accept new monthly data exports with minimal manual intervention.
