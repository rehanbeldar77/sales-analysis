# DAX measure templates

These are standard examples, not a claim about the exact formulas already authored in the supplied PBIX. Check the model's column names and definitions first.

```DAX
Total Sales = SUM(Sales_Data[Total Sales])

Total Quantity = SUM(Sales_Data[Quantity])

Transactions = DISTINCTCOUNT(Sales_Data[Transaction ID])

Average Sales per Transaction =
DIVIDE([Total Sales], [Transactions], 0)

Average Selling Price =
DIVIDE([Total Sales], [Total Quantity], 0)
```

If `Transactions` is already a transaction-level count or a measure in the model, do not replace it blindly. Confirm whether each row represents an item, order, or transaction. The report's existing `Average` measure should also be checked to understand whether it means average transaction value, average unit price, or something else.
