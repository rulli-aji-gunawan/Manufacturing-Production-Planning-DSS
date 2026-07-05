Document Information  
Document Name: Business Requirement  
Version: 1.0  
Project: Manufacturing Production Planning and Decision Support System  
Author: Rulli Aji Gunawan  
Reviewer: ChatGPT (Technical Mentor)  
Status: Draft

---
# Project Overview

## Project Name
### Manufacturing Production Planning and Decision Support System (MPP-DSS)
### One Stop-MPP
---
An enterprise-grade decision support platform  
designed for Production Control engineers  
to perform production planning,  
capacity analysis,  
manpower planning,  
production monitoring,  
and management reporting.

## Project Background
Manufacturing companies are required to meet customer demand while maintaining optimal utilization of machine, manpower, and production capacity. In practice, Production Control engineers must analyze demand fluctuations, machine availibility, manpower allocation, and production performance before making decisions.  
However, decesion making is often supported only by spreadsheets, making scenario analysis time-consuming and increasing the risk of inaccurate planning.  
Therefore this project aims to develope a Manufacturing Production Planning & Decesion Support System (MPP-DSS) that integrates production data and provides analytical insights to support Producton Control and management in decision-making.  

## Project Objective
The objective of this project is to develop a decision support syatem that assists Production Control engineers in:
- evaluating production capacity,
- estimating manpower requirements,
- analyzing production performance,
- simulating production scenarios,
- supporting operational decision making,
- monitoring production KPIs.

## Stakeholders
| Stakeholder | Role | System Usage
|-|-|-|
| Sales | Provide customer demand | Input forecast |
| Production Control | Create production plan | Main user |
| Production Supervisor | Execute production | Update actual production |
| Maintenance | Maintain machines | Update machine status |
| QA | Monitor quality | Input defect data |
| Plant Manager | Decision making | Review dashboard |

## Pain Points
- Customer demand changes frequently.
- Limited production capacity during demand fluctuations.
- Unpredictable downtime.
- OEE changes every day.
- Manpower not always fully available.
- Production planning relies heavily on spreadsheets.
- Difficulties to make "what-if" simulation.

## Functional Requirements
The system shall be able to:
- Import production master data
- Import customer demand
- Calculate production capacity
- Calculate machine utilization
- Estimate manpower requirements
- Monitor production performance
- Simulate production scenarios
- Generate management dashboards
- Export reports

## Non-Functional Requirements
- Easy to use
- Fast calculation
- Modular code structure
- Easy to maintain
- Scalable for future expansion
- Interactive dashboard






