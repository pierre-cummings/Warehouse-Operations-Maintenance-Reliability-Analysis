# Business Findings

## Overview
This document summarizes the key insights from the Warehouse Operations Maintenance & Reliability Analysis project.

The goal is to translate maintenance data into actionable operational and reliability insights that could support real-world decision-making in a warehouse environment.

---

## 1. High-Downtime Equipment Drives Operational Risk

Equipment categories such as conveyors, robots, case erectors, and tape machines contribute significantly to total downtime.

These assets are directly tied to product flow and throughput, meaning failures in these systems have a larger impact on operations.

### Impact
- Increased downtime leads to reduced throughput
- Creates bottlenecks in shipping and sortation
- Impacts overall warehouse efficiency

### Recommendation
Focus preventive maintenance and monitoring on these high-impact equipment categories.

---

## 2. Vendor Repairs Show Higher Cost and Downtime

Vendor-supported repairs generally show:
- higher average repair cost
- longer average downtime

This may be due to:
- response time delays
- scheduling constraints
- higher complexity repairs being routed to vendors

### Impact
- increased operational disruption
- higher maintenance spend

### Recommendation
- review vendor response time expectations
- evaluate which repairs can be brought in-house
- optimize vendor usage for high-complexity tasks only

---

## 3. Maintenance Cost is Concentrated by Location

Certain warehouse locations show higher total maintenance cost and downtime than others.

This may indicate:
- higher equipment usage
- older or more failure-prone assets
- differences in maintenance practices
- higher reliance on vendor repairs

### Impact
- uneven operational performance across sites
- increased cost concentration in specific locations

### Recommendation
- perform deeper site-level analysis
- standardize maintenance practices where possible
- identify high-cost locations for improvement initiatives

---

## 4. Safety-Related Issues Identified Through SQL Analysis

Safety-affected issues were analyzed using SQL queries rather than being fully visualized in the dashboard.

These issues are more commonly associated with:
- forklifts
- pallet jacks and rider pallet jacks
- pallet rack systems
- robotic equipment

### Impact
- increased risk of workplace incidents
- potential compliance and liability concerns

### Recommendation
- track safety-related events separately from general maintenance
- increase inspection focus on safety-critical equipment
- consider adding a dedicated safety dashboard view in future iterations

---

## 5. Operations-Impacted Issues Identified Through SQL Analysis

Operations-affected issues were also analyzed through SQL queries to understand which equipment most impacts workflow.

Common contributors include:
- conveyors
- case erectors
- tape machines
- sortation systems

### Impact
- delays in shipping and receiving
- workflow interruptions
- reduced throughput

### Recommendation
- prioritize operations-critical equipment for preventive maintenance
- ensure spare parts availability
- consider expanding this analysis into a dedicated dashboard page

---

## 6. Repair Provider Analysis Supports Strategy Decisions

Analyzing repair activity by provider shows:
- workload distribution between in-house and vendors
- cost differences
- downtime differences

### Impact
- helps determine optimal repair strategy
- highlights potential inefficiencies

### Recommendation
- expand in-house capabilities where beneficial
- optimize vendor usage for specialized work
- track performance metrics over time

---

## Summary

This analysis demonstrates how maintenance data can be used to:
- identify downtime drivers
- evaluate repair cost and downtime performance
- compare repair ownership strategies
- highlight safety and operational risk areas through SQL analysis

Future improvements could include expanding safety and operations impact analysis into dashboard visualizations.
- support preventive maintenance planning
- enhance safety oversight

The project demonstrates how operational data can be translated into meaningful business insights for warehouse performance improvement.
