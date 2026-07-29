# Enterprise Retail Banking Data Model

## 1. Project Overview

The objective of this project is to design a centralized relational database for a retail banking system. The database will manage customer information, bank accounts, transactions, loans, credit cards, branches, and employees while ensuring data consistency, integrity, and scalability.

---

## 2. Problem Statement

The bank currently maintains customer and banking information across multiple disconnected systems, resulting in duplicate records, inconsistent data, and inefficient reporting. A centralized data model is required to improve data quality, simplify operations, and support future business growth.

---

## 3. Business Objectives

- Design a centralized database for banking operations.
- Maintain accurate and consistent customer information.
- Support multiple bank accounts for a customer.
- Record all financial transactions.
- Manage loan and credit card information.
- Improve data integrity and reduce redundancy.
- Enable efficient reporting and analytics.
- Support future scalability.

---

## 4. Functional Requirements

### 4.1 Customer Management

The system shall:

- Register new customers.
- Store customer personal and contact information.
- Assign a unique Customer ID to every customer.
- Allow customers to update their information.
- Associate every customer with a home branch.

### 4.2 Account Management

The system shall:

- Allow customers to open multiple accounts.
- Support Savings and Current account types.
- Store account balance.
- Record account opening date.
- Maintain account status.
- Associate every account with one branch.

### 4.3 Transaction Management

The system shall:

- Record deposits.
- Record withdrawals.
- Record transfers.
- Store transaction amount.
- Store transaction date and time.
- Maintain transaction status.
- Maintain complete transaction history.

### 4.4 Loan Management

The system shall:

- Store loan applications.
- Support Home, Car, and Personal loans.
- Record loan amount.
- Store interest rate.
- Store EMI amount.
- Track loan status.

### 4.5 Credit Card Management

The system shall:

- Allow customers to own multiple credit cards.
- Store card type.
- Store credit limit.
- Store outstanding balance.
- Store expiry date.
- Track card status.

### 4.6 Branch Management

The system shall:

- Store branch information.
- Maintain branch IFSC code.
- Store branch location.
- Manage customers and accounts under each branch.

### 4.7 Employee Management

The system shall:

- Store employee information.
- Assign employees to branches.
- Maintain employee roles.

---

## 5. Non-Functional Requirements

- Ensure high data integrity.
- Prevent duplicate customer records.
- Maintain referential integrity.
- Support efficient SQL queries.
- Ensure scalability.
- Support secure storage of banking information.
- Support future system enhancements.

---

## 6. Assumptions

- One customer can own multiple accounts.
- One account belongs to only one customer.
- One customer belongs to one home branch.
- One account can have multiple transactions.
- One customer can have multiple loans.
- One customer can own multiple credit cards.
- One employee works in only one branch.

---

## 7. Scope

The project includes the design of:

- Customer Management
- Account Management
- Transaction Management
- Loan Management
- Credit Card Management
- Branch Management
- Employee Management

The project focuses on database design and implementation and does not include user interface development.
