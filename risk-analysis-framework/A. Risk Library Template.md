# Risk Library Entry

## 1. Risk Event Name  
Cross-System Data Mismatch (Roster vs Registration)

## 2. Event Description  
A user record was missing from the roster despite having a valid confirmation ID. Multiple support interactions failed to resolve the issue due to repeated transfers and lack of effective triage. Eventually, it was discovered that the user’s unique ID was available, and upon lookup, the system showed valid scheduled activities. This indicates a cross-system synchronization failure where backend records existed but were not reflected in the operational roster.


## 3. Trigger Points  
- Roster not synchronized with registration system  
- Customer support failed to use ID lookup  
- On-site staff relied solely on roster  

## 4. Risk Type  
- Data synchronization risk  
- Operational workflow risk  
- Identity verification risk  

## 5. Impact  
- Candidate unable to test  
- Escalation to incident report  
- Increased support workload  
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
