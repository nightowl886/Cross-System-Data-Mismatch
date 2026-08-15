# Cross-System-Data-Mismatch

This repository demonstrates how operational incidents can be transformed into structured risk analysis,
providing insights that align with **model risk governance** practices.

---

## 📚 A. Risk Library Template

The risk library template provides a standardized structure to capture incidents:

1. **Risk Event Name**  
2. **Event Description**  
3. **Trigger Points**  
4. **Risk Type**  
5. **Impact Assessment**  
6. **Root Cause Analysis**  
7. **Control Recommendations**  
8. **Lessons Learned**

This template ensures consistency and enables comparison across different risk cases.

---

## 🧩 B. Sample Synthetic Risk Cases

Examples of abstracted, non-sensitive risk scenarios:

- **Cross-System Data Mismatch**  
  Candidate exists in backend systems but is missing from roster.  

- **Identity Verification Failure**  
  Valid ID presented but system fails due to outdated roster.  

- **Workflow Dependency Breakdown**  
  Customer support repeatedly transfers calls without resolution.  

- **Single Source of Truth Missing**  
  Multiple systems hold inconsistent candidate records.  

These synthetic cases illustrate how real-world incidents can be generalized into reusable risk themes.

---

## 🔗 C. Operational Risk ➡ Model Governance Mapping

```

| **Operational Risk Theme**       | **Model Governance Equivalent**       | **Example Control**                          |
|----------------------------------|---------------------------------------|----------------------------------------------|
| Cross-system data mismatch       | Model inventory inconsistency         | Automated reconciliation between registries  |
| Identity verification failure    | Model input validation gap            | ID-first validation of input data            |
| Workflow dependency breakdown    | Model lifecycle governance gap        | Clear triage workflow for model issues       |
| Single source of truth missing   | Lack of unified model documentation   | Centralized model repository with versioning |
| Data synchronization delay       | Model monitoring lag                  | Real-time monitoring dashboards with alerts  |

```
This mapping demonstrates how operational risk analysis skills directly translate into model risk governance practices.

---

## 🎯 Purpose

- Show how **daily operational incidents** can inspire structured risk projects.  
- Provide a framework for **risk documentation, taxonomy, and control design**.  
- Bridge the gap between **operational risk analysis** and **model governance methodologies**.  

---

## 📂 Repository Structure

- `/sql/` → Data extraction and cleaning queries  
- `/tableau/` → Dashboards and visualizations  
- `/risk-analysis-framework/` → Templates, synthetic cases, governance mapping  

---

## 🚀 Next Steps

- Expand synthetic cases with public datasets.  
- Build dashboards to visualize mismatches and controls.  
- Document lessons learned in governance-ready format.  
