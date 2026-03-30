# Dashboard Notes

## Purpose
The Power BI dashboard was designed to analyze warehouse maintenance and reliability performance across multiple facilities.

It focuses on understanding how maintenance activity impacts:
- downtime
- cost
- repair ownership performance

---

## Dashboard Structure

### 1. Executive Overview
Provides a high-level summary of maintenance activity.

Includes:
- total work orders
- total maintenance cost
- total downtime hours
- average repair time (MTTR)

Purpose:
Allows quick understanding of overall performance.

---

### 2. Reliability Analysis
Focuses on identifying equipment and issue categories that drive downtime.

Includes:
- downtime by equipment
- issue frequency by equipment
- warehouse and equipment breakdown

Purpose:
Highlights reliability risks and failure patterns.

---

### 3. Vendor vs In-House Performance
Compares repair ownership performance.

Includes:
- repair volume by ownership type
- average cost comparison
- average downtime comparison
- repair provider breakdown

Purpose:
Supports decisions around repair strategy and resource allocation.

---

## Safety & Operations Analysis Note

Safety-affected and operations-affected issues were analyzed using SQL queries, but were not fully developed into a dedicated dashboard page.

This analysis still supports:
- identification of safety-related risk areas
- identification of operations-critical equipment
- understanding of business impact from maintenance events

Future iterations of this project could expand this analysis into a dedicated dashboard view.

---

## Key Metrics Used
- Total Work Orders
- Total Maintenance Cost
- Total Downtime Hours
- Average Repair Cost
- Average Downtime Hours
- MTTR
- Vendor Repairs
- In House Repairs

---

## Value of the Dashboard
This dashboard demonstrates how maintenance data can be used to:
- identify reliability issues
- evaluate repair performance
- analyze cost and downtime trends
- support operational decision-making
