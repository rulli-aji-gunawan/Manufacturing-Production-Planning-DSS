Document Information  
Document Name: Business Process  
Version: 1.0  
Project: Manufacturing Production Planning and Decision Support System  
Author: Rulli Aji Gunawan  
Reviewer: ChatGPT (Technical Mentor)  
Status: Draft

---
# Business Process

## 1. Overview
This document describes the end-to-end business process of Production Control in transforming customer demand into an executable production plan.

The process covers demand analysis, production planning, capacity evaluation, machine allocation, manpower planning, production execution, and production monitoring.

The objective is to ensure customer demand can be fulfilled while maintaining efficient utilization of available production resources.


## 2. Business Process Flow
Customer Forecast  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⇩  
Production Planning  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⇩  
Capacity Planning  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⇩  
Machine Allocation  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⇩  
Manpower Planning  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⇩  
Production Execution  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⇩  
Production Monitoring  

---

## 3. Process Description

### 3.1 Customer Forecast
### Objective

Receive customer demand as the primary input for production planning.

### Input

- Monthly Forecast
- Customer Order

### Process

Production Control receives customer demand and verifies its completeness before starting the planning process.

### Output

Validated Customer Demand

---
### 3.2 Production Planning
### Objective

Create a production plan based on validated customer demand.

### Input

- Validated Customer Demand
- Production Calendar
- Inventory Information

### Process

Production Control determines production quantity, production schedule, and production priorities.

### Output

Production Plan

---
## 3.3 Capacity Planning

### Objective

Evaluate whether the available production capacity is sufficient to meet the production plan.

### Input

- Production Plan
- Machine Capacity
- Production Calendar
- OEE
- Working Hours

### Process

Production Control calculates the available production capacity and compares it with the required production capacity. If the available capacity is insufficient, alternative actions such as overtime, additional shifts, or production rescheduling are considered.

### Output

Capacity Planning Result

---
## 3.4 Machine Allocation

### Objective

Assign production jobs to available machines based on machine capability and production requirements.

### Input

- Capacity Planning Result
- Machine Master Data
- Machine Availability

### Process

Production Control allocates production to suitable machines while considering machine capacity, availability, and production efficiency.

### Output

Machine Allocation Plan

---
## 3.5 Manpower Planning

### Objective

Determine the manpower required to execute the production plan.

### Input

- Machine Allocation Plan
- Standard Manpower Requirement
- Shift Schedule
- Operator Availability

### Process

Production Control estimates the number of operators required for each production process and adjusts manpower allocation according to production demand and shift availability.

### Output

Manpower Plan

---
## 3.6 Production Execution

### Objective

Execute the approved production plan.

### Input

- Production Plan
- Machine Allocation Plan
- Manpower Plan

### Process

The Production Department performs production activities according to the production plan. Production data such as output, downtime, and production issues are recorded during the execution process.

### Output

Actual Production Data

---
## 3.7 Production Monitoring

### Objective

Monitor production performance and identify any deviations from the production plan.

### Input

- Actual Production Data
- Production Plan

### Process

Production Control compares actual production results with the production plan. Any deviations such as production delays, machine downtime, or quality issues are analyzed to determine corrective actions.

### Output

Production Performance Report

---
## Process Summary

The Production Control business process transforms customer demand into executable production plans through systematic planning, capacity evaluation, resource allocation, production execution, and continuous production monitoring.

This process ensures that production resources are utilized effectively while maintaining the ability to fulfill customer demand.