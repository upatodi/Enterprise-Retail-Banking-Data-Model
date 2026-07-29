# Business Rules

## Customer and Branch

BR-001: A customer must be associated with exactly one home branch.

BR-002: A branch can have zero, one, or many customers.

---

## Customer and Account

BR-003: A customer can own one or more bank accounts.

BR-004: Every account must belong to exactly one customer.

---

## Branch and Account

BR-005: Every account must be maintained by exactly one branch.

BR-006: A branch can manage multiple accounts.

---

## Account and Transaction

BR-007: An account can have zero, one, or many transactions.

BR-008: Every transaction must belong to exactly one account.

---

## Customer and Loan

BR-009: A customer can apply for multiple loans.

BR-010: Every loan belongs to exactly one customer.

---

## Customer and Credit Card

BR-011: A customer can own multiple credit cards.

BR-012: Every credit card belongs to exactly one customer.

---

## Branch and Employee

BR-013: A branch can employ multiple employees.

BR-014: Every employee must work in exactly one branch.

---

## Customer and Address

BR-015: Every customer must have one registered address.

BR-016: Every address belongs to exactly one customer.
