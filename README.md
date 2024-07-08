# Bank Accounts Analysis

## Project Description
The objective of this project is to create a denormalized table containing behavioral indicators for customers, calculated based on their transactions and product holdings. This table will serve as a feature set for a potential supervised machine learning model.

## Database Structure
The database consists of the following tables:

- cliente: Contains customer information.
- conto: Details about the accounts held by customers.
- tipo_conto: Types of accounts available.
- tipo_transazione: Types of transactions performed.
- transazioni: Records of all transactions made by customers.

## Indicators Created
Each indicator is referenced to a single `id_cliente`. The indicators include:

- Age: The age of the customer.
- Number of Outgoing Transactions: Total number of outgoing transactions across all accounts.
- Number of Incoming Transactions: Total number of incoming transactions across all accounts.
- Total Amount of Outgoing Transactions: Sum of the amounts for all outgoing transactions across all accounts.
- Total Amount of Incoming Transactions: Sum of the amounts for all incoming transactions across all accounts.
- Total Number of Accounts Held: Total number of accounts owned by the customer.
- Number of Accounts by Type: Number of accounts owned by the customer, categorized by account type (one indicator per type).
- Number of Outgoing Transactions by Type: Number of outgoing transactions categorized by transaction type (one indicator per type).
- Number of Incoming Transactions by Type: Number of incoming transactions categorized by transaction type (one indicator per type).
- Amount of Outgoing Transactions by Account Type: Sum of the amounts for outgoing transactions categorized by account type (one indicator per type).
- Amount of Incoming Transactions by Account Type: Sum of the amounts for incoming transactions categorized by account type (one indicator per type).

## Summary
This project involves the creation of a comprehensive feature set for customers, derived from transactional and account data. These features will be essential for building a supervised machine learning model to analyze customer behavior. The denormalized table will facilitate efficient data processing and feature extraction, enabling advanced analytics and predictive modeling.
