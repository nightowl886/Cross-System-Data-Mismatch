# Risk Library Entry

## 1. Risk Event Name  
Cross-System Data Mismatch (Roster vs Registration)

## 2. Event Description  
A user record was missing from the roster despite having a valid confirmation ID. Multiple support interactions failed to resolve the issue due to repeated transfers and ineffective triage. Eventually, it was discovered that the user’s unique ID was available, and upon lookup, the system showed valid scheduled activities. This indicates a cross-system synchronization failure where backend records existed but were not reflected in the operational roster.


## 3. Trigger Points  
- Roster not synchronized with registration system  
- Customer support failed to use ID to locate the profile
- Repeated call transfers without effective triage
- On-site staff relied solely on roster

## 4. Risk Type  
- System Data synchronization risk  
- Operational process risk  
- Identity verification risk
- Customer support workflow risk
- Candidate identity verification risk
- Cross-system integrity risk

## 5. Impact  
If not resolved, this issue could lead to:
- Candidate unable to test  
- Delays and escalation to incident report  
- Increased customer support workload  
- Reputation risk for test center

## 6. Root Cause  
- Lack of single source of truth  
- No automated detection for roster mismatch  
- Customer support workflow gaps  

## 7. Controls  
- ID-first verification workflow  
- Multi-source validation checklist  
- Automated mismatch alerts  

## 8. Lessons Learned  
Roster is not authoritative; ID is the most reliable identifier.
