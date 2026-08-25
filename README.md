# Lab 1 – Requirements Engineering & UML Use-Case Modelling

---

## Personal Subscription & Recurring Expense Auditor

**PES University – Dept. of CSE**  
**Problem Statement #32 – Retail, E-Commerce & Finance**

---
## Project Overview
This repository contains the software engineering design and requirements engineering deliverables for the **Personal Subscription & Recurring Expense Auditor** (Problem Statement #32). 

The system serves as a personal finance application designed to:
* Elicit and analyze transaction logs to detect recurring billing patterns.
* Calculate total monthly subscription spending and project burn rates.
* Send automated alerts prior to subscription renewal dates.
* Offer step-by-step cancellation guides to help users eliminate unwanted recurring charges.

---

## Lab Deliverables

| File Name | Format | Description |
| :--- | :--- | :--- |
| **`Requirements_Table.pdf`** | PDF | Contains 5 Functional Requirements (FR-001 to FR-005) and 2 Non-Functional Requirements (NFR-001 & NFR-002) with priority, acceptance criteria, and rationales. |
| **`UML_Use_Case_Diagram.pdf`** | PDF | Formal UML Use-Case Diagram rendering system boundaries, actors, primary use cases, and `<<include>>` / `<<extend>>` relationships. |
| **`UML_Use_Case_Diagram.svg`** | SVG | Scalable vector graphic version of the UML Use-Case Diagram for editable rendering. |
| **`UML_Use_Case_Diagram.xml`** | XML | Raw XML source code of the diagram for direct import into Draw.io. |
| **`Use_Case_Flow.docx`** | DOCX | Detailed specification for UC-01 (Import Transaction Data) including preconditions, postconditions, Main Success Scenario, and Alternate Flow. |
| **`Submission_Checklist.docx`**| DOCX | Checklist verifying completion of all mandatory Lab 1 submission criteria. |

---

## System Architecture & Model Summary

### Primary Actors
1. **Individual User:** Main consumer interacting with subscription management and alerts.
2. **Bank Transaction Source:** Secondary system actor providing raw transaction inputs.
3. **Finance Auditor:** Administrative/auditing stakeholder reviewing spending reports.

### Key Use Cases & Stereotypes
* **UC-01:** Import Transaction Data `<<include>>` **UC-02:** Analyze Recurring Transactions
* **UC-03:** View Subscription Details `<<include>>` **UC-04:** Calculate Monthly Subscription Expenditure
* **UC-06:** Get Cancellation Guidance `<<extend>>` **UC-03:** View Subscription Details

---

## Repository Structure

```text
├── README.md
├── Requirements_Table.pdf
├── Submission_Checklist.docx
├── UML_Use_Case_Diagram.pdf
├── UML_Use_Case_Diagram.svg
├── UML_Use_Case_Diagram.xml
└── Use_Case_Flow.docx
