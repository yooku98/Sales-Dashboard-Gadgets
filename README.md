# Gadget Sales Dashboard (Tableau)

An interactive Tableau Public dashboard of revenue for a small gadget store, broken down by country, product category and month, with stock-level alerts.

**Live dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/william.thompson1921/viz/RevenueofGadgetsbyCountryDashboard/Sheet1)
**Case study:** [Portfolio write-up](https://yooku98.github.io/Portfolio-Website/gadget-sales.html)

## What it shows

- Revenue by country and by product category
- Monthly revenue trend
- Stock-level status per product ("Restock Needed" vs "OK", based on each product's restock threshold)

## Data model

Four small sample CSVs, joined in Tableau:

| File | Key columns |
|---|---|
| `orders.csv` | `order_id`, `customer_id`, `order_date`, `amount_usd`, `product`, `quantity` |
| `customers.csv` | `customer_id`, `name`, `country`, `email` |
| `products.csv` | `product_id`, `product_name`, `category`, `price_usd` |
| `inventory.csv` | `product_id`, `stock_level`, `restock_threshold` |

The customer names and emails are fictional sample data.

## Files

- `Revenue of Gadgets by Country Dashboard.twb`: Tableau workbook (open in Tableau Desktop or Tableau Public)
- `*.csv`: source data

## Tools

Tableau Public
