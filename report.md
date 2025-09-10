# Detailed Bank Transaction Analysis Report (70 Accounts, 2024)

## Overview
The analysis covers:
- **70 Accounts**
- **2,500 transactions**
- **Account Types**: Current and Savings
- **Transaction Types**: Debit, Credit, Reversals, Chargebacks
- **23 cities in Nigeria**
- **₦607,738,020 total transaction value**
- **Year: 2024**

## Insights

### 1. Multi-Location Account Activity
The following accounts carried out transactions in more than one location and are also linked to chargeback issues:  
**ACC1023, ACC1044, ACC1002, ACC1049, ACC1006, ACC1016, ACC1058**

### 2. Chargeback Transactions Analysis
- **45 of 70 accounts (64.29%)** reported chargebacks.  
- These account for **9.69% of total transaction value**.  

**Accounts with chargeback claims resulting from unauthorised transactions and chargeback claims:**  

| Account | Count | Account | Count | Account | Count | Account | Count |
|---------|-------|---------|-------|---------|-------|---------|-------|
| ACC1001 | 2 | ACC1019 | 4 | ACC1038 | 3 | ACC1054 | 3 |
| ACC1002 | 5 | ACC1022 | 2 | ACC1039 | 4 | ACC1056 | 6 |
| ACC1003 | 6 | ACC1023 | 4 | ACC1040 | 4 | ACC1057 | 4 |
| ACC1004 | 3 | ACC1024 | 6 | ACC1042 | 6 | ACC1058 | 3 |
| ACC1006 | 3 | ACC1026 | 6 | ACC1043 | 5 | ACC1060 | 7 |
| ACC1009 | 5 | ACC1027 | 4 | ACC1045 | 4 | ACC1062 | 5 |
| ACC1013 | 2 | ACC1028 | 6 | ACC1048 | 2 | ACC1063 | 5 |
| ACC1014 | 3 | ACC1031 | 4 | ACC1050 | 5 | ACC1064 | 3 |
| ACC1015 | 4 | ACC1034 | 3 | ACC1051 | 4 | ACC1065 | 3 |
| ACC1016 | 3 | ACC1036 | 4 | ACC1052 | 2 | ACC1066 | 8 |
| ACC1017 | 2 | ACC1037 | 4 | ACC1053 | 3 | ACC1069 | 4 |
|         |   |         |   |         |   | ACC1070 | 3 |


### 3. Location-Based Analysis
- Chargebacks due to unauthorized/fraudulent transactions are concentrated in specific cities:  
  - **Ibadan**: 28  
  - **Makurdi**: 22  
  - **Kaduna & Kano**: 19 each  
  - **Owerri & Onitsha**: 15 each  

### 4. Monthly Trend
- **August**: Highest number of transactions (226 in volume).  
- **April**: Highest transaction value (₦56.5m).  
- **January**: Most chargebacks due to unauthorised transactiosn and fraudulent transactions (24 cases, ₦5.5m in value).  
- **March**: Slightly fewer cases (22) of chargebacks due to unathorised transactions and fraudulent transactions but highest value (₦6.29m).  

### 5. Debit Transactions
- **62.52%** of total transaction volume are debits.  
- **Foreign Exchange (FX) Purchases** = 9.68% of debit transactions.  
  - **Owerri**: 13 transactions (10.62%) of total FX transactions ₦3.86m 
  - **Kano**: 13 transactions (9.48%) of total FX transactions, totaling ₦3.4 million  
  - **Ibadan**: 12 transactions (8.44%), with ₦3 million in FX purchases
  - Other cities hover around ₦1 million - ₦2 million, or even less, showing a clear concentration of high value FX transactions in the three locations listed above.

- **Account Maintenance Fee deductions**: Makes up **7.75%** of debit transactions.  
  - Range of values: ₦1,900 – ₦492,069.  
  - These amounts are unusual and may signal:  
    - Fraud disguised as charges  
    - System errors  
    - Insider collusion  

### 6. Credit Transactions
- Credit transactions make up **18%** of total (450 in volume).  
- **26.87% of Credit Transactions** were “Reimbursement for Overcharged Fees”. This amounts to an approximate value of **₦30 million**. 
  - Alarming because these should be rare and low-value.  
  - Possible issues:  
    - Fake refund narratives  
    - Insider activity  
    - Illegal funds disguised as reimbursements  
    - Weakness in classification controls
    - Possible reversal of Account Maintenance Fees. However, no information was provided to prove that. 

### 7. Time Trend Analysis
- Transactions carried out from **12 AM – 5 AM** accounts for **20–26%** across all transaction types.  
- Further breakdown is given below:  
  - Credit: 113 transactions (25.11% of total credit transactions)  
  - Debit: 382 transactions (24.44% of total debit transactions)
  - Reversals: 28 transactions (21.71% of total reversals)
  - Chargebacks: 89 transactions (24.86% of total chargebacks)  

**MoM Trends**:  
- **Volumes**: Seasonal cycle with declines in mid-year (July weakest at -9%) and rebounds in August (+16%).  
- **Values**: More volatile, peaking in April (+16%), rebounding in August (+28%), and dipping again in Sep–Oct.  

## Recommendations

### 1. Investigate Accounts that carried out transactions in multiple locations
- Review flagged accounts in Insightsc 1 above (e.g., ACC1023, ACC1044, ACC1002).  
- Perform KYC reinvestigation.  
- Analyze device/IP logs and behavioral patterns and flag any anormalies.  

### 2. High-Risk Cities
- Investigate Ibadan, Makurdi, Kaduna, Kano, Owerri, and Onitsha as these locations account for the highest cases off chargebacks as a result of unathorised transactions and fraudulent activities.  
- Review why January and March had unusually high chargeback values.  

### 3. Account Maintenance Fee Audit
- Forensic audit on fees above normal limits.  
- Check if system-generated or manually keyed.  
- ₦492,069 entries may suggest fraud.  

### 4. Reimbursement Transactions
- Investigate ₦30m “Reimbursement for Overcharged Fees.”  
- Verify fee type, authorization, funding source, and recipient accounts.  
- Check if linked to abnormal maintenance fees.  

### 5. High-Risk Time Periods
- Flag 12 AM – 5 AM transactions for enhanced monitoring.  
- Apply **two-factor authentication** for debits, chargebacks, reimbursements, and FX purchases.

  **A sheet on the Excel file contains the full Insights and Recommendatiosn**
