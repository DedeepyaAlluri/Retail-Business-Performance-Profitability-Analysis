# Retail Profitability & Discount Analysis

## Question
Do higher discounts hurt profitability, and which products and categories are weakest on margin?

## Data
180 simulated retail orders (2025) with sales, profit, discount (0–20%), category, product and region.

## Method
Excel pivot tables for exploration; Power BI dashboard with measures such as
Margin % = total profit ÷ total sales (not an average of order margins).

## Findings
| Discount level | Margin |
|---|---|
| 0–10% | 14.3% |
| 15–20% | 4.5% |

- Orders at 15%+ discount: 41% of sales, 18% of profit.
- Furniture: highest sales, lowest margin (8.6% vs. 11.6% for Technology).
- Table is the lowest-margin product (6.5%).
- Margins by region were similar (about 10%), so region is not a driver.

## Recommendation
Cap discounts at 10% and require approval above that.

## Limitations
Only 180 orders, and simulated data. I did not test whether high-discount orders are concentrated in low-margin products, so this shows an association, not proof of cause.

## Files
`Dashboard Of Retail Profitability.png

