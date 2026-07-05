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
#### 3.1.1 Objective

Receive customer demand as the primary input for production planning.

#### 3.1.2 Input

- Monthly Forecast
- Customer Order

#### 3.1.3 Process

Production Control receives customer demand and verifies its completeness before starting the planning process.

#### 3.1.4 Output

Validated Customer Demand

---
### 3.2 Production Planning
#### 3.2.1 Objective

Create a production plan based on validated customer demand.

#### 3.2.2 Input

- Validated Customer Demand
- Production Calendar
- Inventory Information

#### 3.2.3 Process

Production Control determines production quantity, production schedule, and production priorities.

#### 3.2.4 Output

Production Plan

---
## 3.3 Capacity Planning

#### 3.3.1 Objective

Evaluate whether the available production capacity is sufficient to meet the production plan.

#### 3.3.2 Input

- Production Plan
- Machine Capacity
- Production Calendar
- OEE
- Working Hours

#### 3.3.3 Process

Production Control calculates the available production capacity and compares it with the required production capacity. If the available capacity is insufficient, alternative actions such as overtime, additional shifts, or production rescheduling are considered.

#### 3.3.4 Output

Capacity Planning Result

---
## 3.4 Machine Allocation

#### 3.4.1 Objective

Assign production jobs to available machines based on machine capability and production requirements.

#### 3.4.2 Input

- Capacity Planning Result
- Machine Master Data
- Machine Availability

#### 3.4.3 Process

Production Control allocates production to suitable machines while considering machine capacity, availability, and production efficiency.

#### 3.4.4 Output

Machine Allocation Plan

---
## 3.5 Manpower Planning

#### 3.5.1 Objective

Determine the manpower required to execute the production plan.

#### 3.5.2 Input

- Machine Allocation Plan
- Standard Manpower Requirement
- Shift Schedule
- Operator Availability

#### 3.5.3 Process

Production Control estimates the number of operators required for each production process and adjusts manpower allocation according to production demand and shift availability.

#### 3.5.4 Output

Manpower Plan

---
## 3.6 Production Execution

#### 3.6.1 Objective

Execute the approved production plan.

#### 3.6.2 Input

- Production Plan
- Machine Allocation Plan
- Manpower Plan

#### 3.6.3 Process

The Production Department performs production activities according to the production plan. Production data such as output, downtime, and production issues are recorded during the execution process.

#### 3.6.4 Output

Actual Production Data

---
## 3.7 Production Monitoring

#### 3.7.1 Objective

Monitor production performance and identify any deviations from the production plan.

#### 3.7.2 Input

- Actual Production Data
- Production Plan

#### 3.7.3 Process

Production Control compares actual production results with the production plan. Any deviations such as production delays, machine downtime, or quality issues are analyzed to determine corrective actions.

#### 3.7.4 Output

Production Performance Report

---
## Process Summary

This business process enables Production Control to transform customer demand into executable production plans through structured planning, capacity evaluation, resource allocation, production execution, and performance monitoring.

The process serves as the operational foundation for decision-making to ensure customer demand is fulfilled while maximizing the utilization of available production resources.