# Data Dictionary

| Column Name | Description                   |
| ----------- | ----------------------------- |
| Invoice     | Unique transaction identifier |
| StockCode   | Product identifier            |
| Description | Product description           |
| Quantity    | Number of units purchased     |
| InvoiceDate | Date and time of transaction  |
| Price       | Product unit price            |
| CustomerID  | Unique customer identifier    |
| Country     | Customer country              |
| Revenue     | Quantity × Price              |
| YearMonth   | Derived reporting period      |

## Derived Fields

### Revenue

Revenue generated from each transaction.

Formula:

Revenue = Quantity × Price

### YearMonth

Created for trend analysis and monthly reporting.

### RFM Metrics

* Recency
* Frequency
* Monetary Value

These fields were created during customer segmentation.
