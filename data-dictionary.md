# Data dictionary (fields referenced by the report)

The report layout references the following fields/measures from a model entity named `Sales_Data`. Descriptions below are inferred from their names; validate the exact definitions in Power BI.

| Field / measure | Likely meaning | Validation to perform |
|---|---|---|
| Date | Sale date | Confirm data type, range and granularity |
| City | Customer/store city | Check spelling and geographic completeness |
| Brand | Mobile phone brand | Check category consistency |
| Mobile Model | Product model | Check duplicate / inconsistent labels |
| Payment Method | Payment channel | Confirm categories |
| Day Name | Weekday label | Confirm sort order follows weekday number |
| Customer Ratings | Customer rating value | Confirm scale and missing values |
| Total Sales | Sales amount measure/column | Confirm currency and aggregation |
| Total Quantity | Units sold measure | Confirm returns/cancellations treatment |
| Transactions | Transaction count measure | Confirm distinct transaction definition |
| Average | Average measure | Confirm its business definition before presenting |

Other fields may exist in the model. This list only covers fields observed in the report layout.
