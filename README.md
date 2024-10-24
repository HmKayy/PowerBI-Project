
# Simple PowerBI Dashboard
![CoffeeShop](https://github.com/user-attachments/assets/2ddf9ac5-c105-4e65-b5db-8a3cde02c160)
This project aims to help me get familiarised with how to transform and create visualizations in PowerBI with a simple analysis of said visualizations.
The project can be accessed through the PowerBI project uploaded to my GitHub

## Problem Statement

This dashboard is used to help the business owner understand their customers and their behavior. This dashboard aims to help the business owner assess their product popularity as well as revenue generated.

## Steps taken

Step 1: Data was loaded into PowerBI, the original data was taken from Kaggle (https://www.kaggle.com/code/ahmedabbas757/coffee-shop-sales/input) in the form of a .xlsx file.

Step 2: Data transformation. The original "transaction_date" was transformed into 4 new columns "Weekday", "Week", "Month", and "Date". "transaction_time" was reduced to only giving the hours. "product_detail" was split into "Product Detail" and "Size" based on the suffix of "Rg", "Lg", "Sm". A new "Transaction Revenue" was also added by multiplying "product_quantity" and "unit_price".

Step 3: The 6 visualizations and 4 number cards were made to highlight the progress as well as explore the growth of the Coffee Chain.

## Simple Analysis
- Number of Products Sold vs Revenue by Product:

Though most of the top-selling products also generated the corresponding amount of revenue, "Sustainably Grown Organic" coffee is a clear outlier with only around 9000 products being sold while generating over 26,000$.
- Drink sizes:

The most common size of drink for the Coffee Chain is the default regular, which might suggest that the

- Revenue:
  
Overall, the 3 store locations perform similarly with each making up 30% of the revenue generated by the Chain. From the revenue per month, it is clear that the Chain is growing despite the drop in performance in February. The shops received the most customers during the morning rush, receiving more than double the number of customers when compared with any other time during the day.


