# Customer Revenue Analytics & ML-Based User Targeting

## Project Overview

This project develops a customer revenue analytics and machine learning framework for an e-commerce business.

The objective is to transform raw transaction-level data into customer-level insights that can help a business understand purchasing behavior, predict future purchase likelihood, estimate potential basket value, and identify customers with higher expected revenue opportunities.

The project combines:

- Transaction-level data analysis
- Customer-level feature engineering
- Behavioral customer segmentation
- Future purchase prediction
- Basket value prediction
- Expected revenue estimation
- Revenue-based customer targeting

---

## Business Problem

An e-commerce business may have a large volume of historical transaction data, but raw transactions alone do not clearly indicate:

- Which customers are likely to purchase again
- How frequently customers purchase
- How much revenue each customer generates
- What the customer's typical basket value is
- Which customers are recently active or inactive
- Which customers have higher return behavior
- Which customers represent greater future revenue opportunities

The goal of this project is to convert historical transaction data into actionable customer-level information that can support data-driven marketing and customer targeting decisions.

---

## Dataset

The project uses a historical e-commerce transaction dataset representing customer purchasing and return activity.

The dataset contains approximately 700,000 transaction-level records.

### Main Columns

| Column | Description |
|---|---|
| `EventID` | Identifier for a basket/transaction |
| `EventType` | Type of event, such as purchase or return |
| `ProductID` | Unique product identifier |
| `ProductName` | Product description |
| `Quantity` | Number of units involved in the transaction |
| `EventDateTime` | Date and time of the transaction |
| `UnitPrice` | Price per unit |
| `UserID` | Customer identifier |
| `LineValue` | Monetary value of the transaction line |

The raw dataset is not included in this repository because of its size.

---

# Project Workflow

```text
Raw Transaction Data
        |
        v
Data Cleaning & Validation
        |
        v
Transaction-Level Revenue Analysis
        |
        v
Customer-Level Feature Engineering
        |
        v
Behavioral Customer Segmentation
        |
        v
Future Purchase Prediction
        |
        v
Expected Basket Value Prediction
        |
        v
Expected Revenue
        |
        v
Revenue Targeting Tiers
        |
        v
Customer Targeting Framework
