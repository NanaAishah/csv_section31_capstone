# Cafe Sales — Dataset

Dataset for the **CSV Commandos: Data Operations Automation** capstone
(Section 31 — Python CSV Module).

## Files

| File | Delimiter | Rows | Notes |
|------|-----------|------|-------|
| `sales_north.csv` | Comma (`,`) | ~3,333 | Standard CSV |
| `sales_south.csv` | Semicolon (`;`) | ~3,333 | Requires a custom dialect |
| `sales_east.csv`  | Comma (`,`) | ~3,334 | Standard CSV |


## Columns

- `Transaction ID` — unique identifier for each transaction
- `Item` — product sold (may contain missing/invalid values)
- `Quantity` — number of items sold (may be missing)
- `Price Per Unit` — price of one unit
- `Total Spent` — total for the transaction (may be inconsistent)
- `Payment Method` — Cash, Credit Card, etc. (may be missing)
- `Location` — In-store, Takeaway (may be missing)
- `Transaction Date` — date of the transaction

## Data quality

This dataset contains **intentional real-world data issues**, including:
- Missing values (empty fields)
- Invalid entries such as `ERROR` and `UNKNOWN`
- Inconsistent text formatting
- Rows where `Total Spent` does not match `Quantity × Price Per Unit`

This is deliberate — handling these issues is part of the capstone.

## Attribution

Dataset: *Cafe Sales — Dirty Data for Cleaning Training* by Ahmed Mohamed (Kaggle).  
Licensed under **CC BY-SA 4.0**.  
https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training

For educational and non-commercial use only.
