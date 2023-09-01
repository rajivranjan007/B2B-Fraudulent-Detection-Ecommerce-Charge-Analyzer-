# B2B-Fraudulent-Detection-Ecommerce-Charge-Analyzer-
This repository houses an assignment solution for an ecommerce company's delivery charge analysis. The project involves data manipulation, charge comparison, and discrepancy reporting between the company and courier partners. Implemented in Python, with results presented in Excel workbooks.
## Input Datasets

The input data comprises the following datasets:

1. **Website Order Report**: Lists Order IDs, products (SKUs) in each order, and payment types.
2. **Warehouse-to-Pincode Mapping**: Maps warehouse and delivery pincodes to zones.
3. **SKU Master**: Contains product weights for weight calculations.
4. **Courier Company Invoice (CSV)**: Includes AWB Numbers, Order IDs, weights, pincodes, charges, and shipment types.
5. **Courier Charges Rate Card**: Provides charge details based on weight slabs and pincodes.

## Output Data

The main output is presented in the `Result.xlsx` Excel workbook, which contains:

### Order-Level Analysis

| Order ID | AWB Number | Total Weight (X) | Weight Slab (X) | Total Weight (Courier) | Weight Slab (Courier) | ... |
| -------- | ---------- | ---------------- | --------------- | ---------------------- | -------------------- | --- |
| ...      | ...        | ...              | ...             | ...                    | ...                  | ... |

### Summary Table

| Description                                 | Count | Amount (Rs.) |
| ------------------------------------------- | ----- | ------------ |
| Total Orders where X has been correctly charged | 12    | 507.6        |
| Total Orders where X has been overcharged     | 382   | 33044.2672   |
| Total Orders where X has been undercharged    | 7     | 109.2        |

## Submission

Submit your completed solution along with the `Result.xlsx` Excel workbook and your code in the chosen programming language.

## Author
Rajiv Ranjan Kumar
