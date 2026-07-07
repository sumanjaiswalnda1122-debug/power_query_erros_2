# Power Query Errors Practice — 2

Practicing common **Power Query (Get & Transform)** data-cleaning techniques in Power BI, using a mock sales order dataset with assignment questions and solutions.

## Dataset
An "Orders" table (`power_query_erros_2.xlsx`) with intentional data-quality issues:
- Duplicate Order IDs
- Inconsistent text casing ("rahul sharma", "PRIYA PATEL", "mumbai")
- Blank values in Quantity, Sales, Customer Name, and Email
- Mixed-case city/product names

## Assignment Questions & Solutions
| # | Task | Power Query Command |
|---|------|----------------------|
| 1 | Replace "CPU" with "Desktop CPU" | Transform → Replace Values |
| 2 | Fill blank Quantity with 1 | Replace Values (null → 1) |
| 3 | Fill blank Sales with 0 | Replace Values (null → 0) |
| 4 | Fill blank Customer Name | Replace Values (null → "Unknown Customer") |
| 5 | Fill blank Email | Replace Values (null → "Not Available") |
| 6 | Convert names to Proper Case | Transform → Format → Capitalize Each Word |
| 7 | Convert city to UPPERCASE | Transform → Format → UPPERCASE |
| 8 | Remove fully blank rows | Home → Remove Rows → Remove Blank Rows |
| 9 | Remove rows with null Quantity | Filter → Remove Null |
| 10 | Fix column data types | Transform → Data Type |
| 11 | Rename a column | Double-click column header |
| 12 | Sort data descending | Sort Descending |

## Files
- `error 2 assignment.pbix` — Power BI file with the cleaning steps applied in Power Query
- `power_query_erros_2.xlsx` — source data, assignment questions (Sheet2), and solution reference (Sheet3)

## Skills demonstrated
Replace Values, handling blanks/nulls, text casing transformations, removing blank/null rows, data type conversion, column renaming, sorting.
