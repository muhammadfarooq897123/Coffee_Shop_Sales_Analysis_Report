# Coffee Shop Sales Analysis

A data analysis project that explores coffee shop transaction data to find profitable and loss-making products and to forecast future sales.

## Dataset

`Coffee Shop Sales.xlsx` contains about 149,000 transactions with these columns:

- **Transaction:** transaction_id, transaction_date, transaction_time, transaction_qty
- **Store:** store_id, store_location
- **Product:** product_id, unit_price, product_category, product_type, product_detail

A `total_sales` column (quantity × unit price) is derived during analysis.

## What the project covers

1. **Data cleaning:** checking for missing values, removing duplicate transactions
2. **Exploratory analysis:** best-selling products and revenue by category
3. **Profit and loss analysis:** top 10 profitable and top 10 loss-making products
4. **Sales forecasting:** daily and monthly sales forecast using an ARIMA(5,1,0) model
5. **Recommendations:** pricing, bundling, inventory, and promotion ideas

## Key findings

- Beverages (lattes, cappuccinos, espresso drinks) consistently outsell snacks and merchandise.
- Sales are higher on weekends.
- Monthly sales show a steady upward trend in the forecast.
- Merchandise and some baked goods appear as loss-making items.

> Note: the dataset has no cost data, so profit figures rely on assumed margins.

## Files

- `Code.ipynb`: analysis notebook
- `Coffee Shop Sales.xlsx`: dataset
- `Coffee_Shop_Sales_Analysis_Report.pdf`: full written report

## How to run

1. Clone the repository:
   `git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git`
2. Install the libraries:
   `pip install pandas numpy matplotlib seaborn statsmodels openpyxl jupyter`
3. Launch the notebook:
   `jupyter notebook Code.ipynb`

## Author

Your Name
