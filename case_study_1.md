---
layout: default
title: End-to-End Claim Management Optimization
---
### Introduction
>Throughout what follows, the process described is that of a customer return followed by a claim. Failures will be identified, modeled, and a proposed solution will be resolved.
---
### Process description
The customer submits a complaint to the company after receiving the package. 
Customer Service receives and reviews the claim, deciding either to initiate the return process or to escalate the matter to the Legal Department. 
In the event of legal action, the return procedure is immediately suspended. If the return is deemed legitimate, 
the customer receives an email requesting they ship the product back within 30 days; otherwise, the process is terminated and marked as aborted.

Once the product is received, technicians perform a quality inspection to assess its condition. 
If the item is in good condition and the defect originated during production, 
the Accounting Department is notified to issue a full 100% refund. 
If the product was damaged by the customer, a notification is sent to Accounting to process a partial refund of 85%, or 70% if the product is severely damaged.

Simultaneously, the technicians log the product details into the Excel database and store the item in the warehouse. 
Meanwhile, the accountant calculates the final refund amount and executes the payment, thus concluding the process.

---
### Interpretation of the situation
The process is structured around strict decision-making flows where technical and accounting actions are interdependent.

Receipt & Validation of the Complaint: Upon receiving the complaint, Customer Service analyzes the claim and determines the appropriate course of action:
- Case A (Legitimate): Initiation of the return procedure. The customer is notified and has a 30-day window to return the product.
- Case B (Abusive/Slanderous): Immediate termination of the return flow and escalation to legal counsel for defamation proceedings.

Return Period Management: If the product is not received within the 30-day deadline, the procedure is permanently aborted.
Simultaneous Technical Analysis & Accounting Execution: Once the claim's legitimacy is established and the product is received, 
a technical assessment is performed to evaluate its condition and determine the root cause of the issue.
After the analysis, data is logged into the system, and the product is moved to the warehouse. Simultaneously, 
the Accounting Department is contacted to issue a refund based on the following business rules:
- 100% Refund: If the issue is a production or the customer defect AND the product is in good condition.
- 85% Refund: If the issue is customer-related BUT the product is damaged.
- 70% Refund: If the issue is customer-related AND the product is  very damaged.

Closure: The process concludes with an automated notification sent to the customer once the Accounting Department has finalized the transfer.

---
### Problem Statement
An audit of the current Excel-based system reveals several critical flaws regarding task synchronization and data integrity:

- Lack of Parallelism: Currently, the process relies on a linear 'handover'—technicians fill out their reports, and accounting must then manually consult the file to perform calculations. 
This sequential workflow causes data reading errors and significant payment delays.

- Business Rule Complexity: The multi-tiered refund structure (100%, 85%, 70%) based on the intersection of two variables (Issue Source vs. 
Product Condition) makes manual data entry in Excel extremely high-risk for financial inaccuracies.

- Invisibility of Legal Exceptions: Claims escalated to the Legal Department (e.g., defamation cases) often fall off 
the standard tracking radar, creating a disconnect between Customer Service and the Legal team.

- Inefficient Deadline Management (Time-Outs): No automated alerts are generated at the 30-day mark (J+30). This forces a manual, 
line-by-line review to identify expired claims that should be aborted, leading to wasted operational hours."
---
### Proposition of solution
>In this phase, I optimized the manual claim process by implementing a structured data model and automated calculation rules.

#### Key Improvements:
* **Logic Automation:** Replaced manual refund estimations with a precise SQL-based logic (`CASE WHEN`) and Excel formulas.
* **Financial Accuracy:** Developed a calculation engine that automatically applies 70%, 85%, or 100% refund rates based on product condition and issue source.
* **Time-Fencing:** Integrated a "30-day rule" to automatically flag or abort expired claims, protecting company cash flow.

#### Tools & Implementation:
* **SQL:** Enforced business constraints using `ENUM` types and automated updates.
* **Excel Power Query:** Consolidated multiple data sources to create a unified reporting view.
* **Formulas:** Used nested `IF` and `AND` (WENN/UND) logic to ensure zero errors on edge cases (e.g., "Unknown" sources).

> **Result:** Reduced manual processing time by an estimated 60% and eliminated human calculation errors.
