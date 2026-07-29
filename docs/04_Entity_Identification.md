# Entity Identification

## Overview

Based on the business requirements, the following business entities have been identified for the Enterprise Retail Banking System.

---

## 1. Customer

**Description:**
Represents an individual who uses the bank's services.

**Responsibilities:**

- Stores customer information.
- Owns one or more bank accounts.
- Can apply for multiple loans.
- Can own multiple credit cards.
- Belongs to one home branch.

---

## 2. Branch

**Description:**
Represents a physical bank branch.

**Responsibilities:**

- Manages customers.
- Manages accounts.
- Employs bank staff.
- Stores branch information.

---

## 3. Account

**Description:**
Represents a bank account owned by a customer.

**Responsibilities:**

- Stores account details.
- Maintains current balance.
- Records account status.
- Links customer and branch.
- Supports financial transactions.

---

## 4. Transaction

**Description:**
Represents every financial activity performed on an account.

**Responsibilities:**

- Records deposits.
- Records withdrawals.
- Records transfers.
- Stores transaction history.

---

## 5. Loan

**Description:**
Represents a loan issued by the bank.

**Responsibilities:**

- Stores loan details.
- Tracks repayment information.
- Maintains loan status.

---

## 6. Credit Card

**Description:**
Represents a credit card issued to a customer.

**Responsibilities:**

- Stores card information.
- Maintains credit limit.
- Tracks outstanding balance.
- Stores expiry details.

---

## 7. Employee

**Description:**
Represents a bank employee.

**Responsibilities:**

- Works at one branch.
- Performs banking operations.
- Supports customer services.

---

## 8. Address

**Description:**
Represents the registered address of a customer.

**Responsibilities:**

- Stores address details.
- Associates address with a customer.
