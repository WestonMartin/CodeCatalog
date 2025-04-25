# CodeCatalog
A comprehensive list of all payors and associated codes related to billing across EMRs and Disciplines 

# <ins>Code Compilation</ins>
- Acquire a code catalog from the specific payor's website on all current codes that have the potential to be billed by the company.
- Create a standard naming convention for each payor that corresponds to the name of the payors within the EMRs for reference.
- Denote whether the code is a /Visit or /Unit reimbursement. 
- Add the associated /Visit, /Hour, or /Unit reimursement rate in a "Rate/Unit" or "Rate/Hour" column.
- Include a calcuation from a /Unit reimbursement to the "Rate/Hour" column via a formula:
  - _=IF(D2="Visit",E2,(E2*4)_
  - _D = Visit/Unit | E = Rate / Unit_
- Add the associated Umbrella of Service (Speech Therapy, Occupational Therapy, Behavior Therapy, etc)
- Add whether the code is associated with a technician or a licensed therapist.

# <ins>Use Case</ins>
- Use this sheet as a reference for calculating reimbursement of services in EMRs.
- Used when the EMR does not have the capacity to give you a per code per payor breakdown within their system.
- All you need is the following to accurately calculate the reimbursement for that specific instance.
  - _Code_
  - _Payor_
  - _Units_
