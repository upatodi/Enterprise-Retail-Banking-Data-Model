# Entity Attributes

## Customer

| Attribute | Data Type | Key |
|-----------|-----------|-----|
| CustomerID | INT | Primary Key |
| FirstName | VARCHAR(50) | |
| LastName | VARCHAR(50) | |
| DOB | DATE | |
| Gender | VARCHAR(10) | |
| Phone | VARCHAR(15) | |
| Email | VARCHAR(100) | |
| PAN | VARCHAR(10) | |
| Aadhaar | VARCHAR(12) | |
| BranchID | INT | Foreign Key |

---

## Branch

| Attribute | Data Type | Key |
|-----------|-----------|-----|
| BranchID | INT | Primary Key |
| BranchName | VARCHAR(100) | |
| IFSC | VARCHAR(20) | |
| City | VARCHAR(50) | |
| State | VARCHAR(50) | |

---

## Account

| Attribute | Data Type | Key |
|-----------|-----------|-----|
| AccountID | INT | Primary Key |
| AccountNumber | VARCHAR(20) | Unique |
| CustomerID | INT | Foreign Key |
| BranchID | INT | Foreign Key |
| AccountType | VARCHAR(20) | |
| Balance | DECIMAL(15,2) | |
| OpenDate | DATE | |
| Status | VARCHAR(20) | |

---

## Transaction

| Attribute | Data Type | Key |
|-----------|-----------|-----|
| TransactionID | BIGINT | Primary Key |
| AccountID | INT | Foreign Key |
| Amount | DECIMAL(15,2) | |
| TransactionType | VARCHAR(20) | |
| TransactionDate | DATETIME | |
| Status | VARCHAR(20) | |
| Description | VARCHAR(255) | |

---

## Loan

| Attribute | Data Type | Key |
|-----------|-----------|-----|
| LoanID | INT | Primary Key |
| CustomerID | INT | Foreign Key |
| LoanType | VARCHAR(30) | |
| LoanAmount | DECIMAL(15,2) | |
| InterestRate | DECIMAL(5,2) | |
| EMI | DECIMAL(15,2) | |
| TenureMonths | INT | |
| Status | VARCHAR(20) | |

---

## CreditCard

| Attribute | Data Type | Key |
|-----------|-----------|-----|
| CardID | INT | Primary Key |
| CustomerID | INT | Foreign Key |
| CardNumber | VARCHAR(20) | |
| CardType | VARCHAR(20) | |
| CreditLimit | DECIMAL(15,2) | |
| OutstandingBalance | DECIMAL(15,2) | |
| ExpiryDate | DATE | |
| Status | VARCHAR(20) | |

---

## Employee

| Attribute | Data Type | Key |
|-----------|-----------|-----|
| EmployeeID | INT | Primary Key |
| BranchID | INT | Foreign Key |
| FirstName | VARCHAR(50) | |
| LastName | VARCHAR(50) | |
| Role | VARCHAR(50) | |
| Email | VARCHAR(100) | |
| Phone | VARCHAR(15) | |

---

## Address

| Attribute | Data Type | Key |
|-----------|-----------|-----|
| AddressID | INT | Primary Key |
| CustomerID | INT | Foreign Key |
| AddressLine | VARCHAR(255) | |
| City | VARCHAR(50) | |
| State | VARCHAR(50) | |
| Pincode | VARCHAR(10) | |
