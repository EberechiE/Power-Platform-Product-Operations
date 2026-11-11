# Fictional Sample Data

This folder contains fictional records illustrating the logical data relationships used by the Product Operations Management Platform.

No production or organizational data is included.

---

## Data Model

The application follows a hierarchical operational structure:

```text
Product
   ↓
Feature
   ↓
Task
   ↓
Comment

```
A product can contain multiple features.

Each feature can contain multiple delivery tasks.

Each task can contain multiple progress comments.

Files
product-operations-sample.csv

Illustrates feature-level information including:

Product
Capability
Business objective
Status
Ownership
Priority
Target delivery date
Release cycle
tasks-sample.csv

Illustrates task records linked to individual features using FeatureID.

comments-sample.csv

Illustrates progress comments linked to tasks using TaskID.
## Example Relationship
```
Fleet Analytics
      │
      ▼
F001 - Adoption Dashboard
      │
      ├── T001 - Define adoption KPIs
      │
      └── T002 - Build reporting data model
                    │
                    ├── C001 - Initial data model structure completed
                    └── C002 - KPI validation in progress
```
## Portfolio Disclaimer

All names, products, records, dates and scenarios contained in these datasets are fictional and created exclusively for portfolio demonstration.

They do not represent production company data, customers, employees or commercial information.
