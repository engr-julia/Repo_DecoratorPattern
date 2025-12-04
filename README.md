# CIMB Decorator Pattern – Savings Account, GSave, UpSave

## Problem Statement

CIMB is a digital bank that offers GSave and UpSave savings accounts. As with a typical Savings Account, it contains an accountNumber, accountName, and a balance for that account.

- The typical savings account offers an interest rate of **1%**.  
  Benefits: **"Standard Savings Account"**

- The GSave account offers an interest rate of **2.5%**.  
  Benefits: **Standard Savings Account + "GCash Transfer"**

- The UpSave account offers the highest interest rate of **4.0%**.  
  Benefits: **Standard Savings Account + "With Insurance"**

You must develop a **Decorator Pattern** following the UML diagram provided.  
`Cimb.java` must NOT be modified except for inserting a package name.

The system must display:

- Account information  
- Account type  
- Interest rate  
- New balance with interest  
- Benefits  

---

## Output Required

Account number: 1234
Account name: Juan Dela Cruz
Balance: 10000.0
Account type: Savings Account
Interest rate: 0.01
New balance: 10100.0
Benefits: Standard Savings Account
----------------------
Account number: 1234
Account name: Juan Dela Cruz
Balance: 10000.0
Account type: GSave
Interest rate: 0.025
New balance: 10250.0
Benefits: Standard Savings Account, GCash Transfer
----------------------
Account number: 1234
Account name: Juan Dela Cruz
Balance: 10000.0
Account type: UpSave
Interest rate: 0.04
New balance: 10400.0
Benefits: Standard Savings Account, With Insurance
