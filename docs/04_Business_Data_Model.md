Document Information  
Document Name: Business Data Model
Version: 1.0  
Project: Manufacturing Production Planning and Decision Support System  
Author: Rulli Aji Gunawan  
Reviewer: ChatGPT (Technical Mentor)  
Status: Draft

---
# Business Data Model
|Information Group|Business Information|Purpose|
|---|---|---|
|Demand|Customer Demand|To identify customer demand that must be fulfilled.|
|Planning|Production Sequence|To define the optimal sequence of production|
|Production|Actual Production Performance|To evaluate actual production performance against the production plan.|
|Production|WIP Status|To monitoring work-in-process (WIP) throughout the production process.|
|Resource|Machine Availability|To determine whether production machines are available for operation.|
|Resource|Manpower Availability|To identify manpower readiness|
|Resource|Material Availability|To ensure required materials are available before production starts.|
|Resource|Production Time Availability|To determine the effective production time available for execution.|
|Constraint|Maintenance Schedule|To identify maintenance activity that will impact to the capacity|
|Constraint|Quality Hold Status|To identify product on hold due to quality issue|

---
## Summary

The Business Data Model identifies the core business information required by the Production Control process.

These information groups serve as the foundation for the next design stage, where each business information item will be translated into detailed data elements and eventually implemented as datasets and database structures.