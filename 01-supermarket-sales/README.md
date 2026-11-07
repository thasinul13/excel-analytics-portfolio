# 01 – Supermarket Sales

## Business question
Which stores and product categories drive the most sales?

## Data
`Excel_Practice_Supermarket_Sales.xlsx` – 40 sales records from three Sydney stores (Lane Cove, Chatswood, Ryde), 1–14 October.

Columns: Date, Store, Category, Product, Units Sold, Unit Price ($), Revenue (calculated).

## What I did
- Converted the data into an Excel Table, froze the header row, sorted and filtered
- Added a calculated **Revenue** column (Units Sold × Unit Price)
- Calculated total and average revenue with `SUM` and `AVERAGE`
- Built summary tables by category and by store using `COUNTIF` and `SUMIF`
- Used locked references (`$C$2:$C$41`) and structured references (`Table1[Store]`) so formulas copy correctly
- Checked that every summary adds back to the overall totals (40 sales, $6,541.64)

## Findings
| Category | Sales | Revenue |
|---|---|---|
| Frozen | 14 | $2,355.78 |
| Dairy | 10 | $2,181.78 |
| Produce | 8 | $1,078.80 |
| Bakery | 8 | $925.28 |

| Store | Sales | Revenue |
|---|---|---|
| Ryde | 18 | $3,071.81 |
| Lane Cove | 12 | $2,055.62 |
| Chatswood | 10 | $1,414.21 |

- **Frozen** is the top category, bringing in about 36% of total revenue.
- **Dairy** is close behind with fewer sales – each Dairy sale is worth more on average (~$218 vs ~$168 for Frozen), driven by higher-priced cheese.
- **Ryde** earns the most revenue, but because it has the most sales, not larger ones – revenue per sale at Ryde and Lane Cove is about the same (~$171), while Chatswood is lowest (~$141).

## Screenshots
<img width="2541" height="1199" alt="image" src="https://github.com/user-attachments/assets/9c709df8-e8d2-4d93-83f0-f4e156fe1a76" />
