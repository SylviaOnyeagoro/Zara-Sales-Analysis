**ZARA SALES DATA ANALYSIS**

**Purpose of the Project:**

The project aims at gaining insights on the sales at Zara and to gain understanding of the various factors governing them.

**About Data:**

The dataset was gotten from Kaggle. This Zara sales dataset contains information about product sales from Zara stores over a specific period of time. The dataset includes various attributes relevant to sales, such as product ID, product name, product category, price, sales volume, sales date, and store location.This dataset contains sales records in the store and it contains 16 columns and 232 rows

1.	Product ID: Unique identifier for each product.
2.	Product Position: The position of the product in the catalog or store layout.
3.	Promotion: Indicator of whether the product is currently on promotion or not.
4.	Product Category: The category of the product, such as clothing, accessories, shoes, etc.
5.	Seasonal: Indicator of whether the product is part of a specific seasonal collection.
6.	Sales Volume: The quantity of products sold.
7.	Brand: Brand of the product.
8.	URL: Product URL (e.g., if the product is sold online).
9.	SKU: Stock Keeping Unit, a unique code used to identify items available for sale.
10.	Name: Name of the product.
11.	Description: Description of the product.
12.	Price: Price of the product.
13.	Currency: Currency of the product price.
14.	Scraped at: The time when the data was scraped (e.g., in web scraping process).
15.	Terms: Terms or conditions of the product.
16.	Section: Section or category where the product is sold in the store (e.g., women's clothing, men's clothing, children's clothing, etc.).

**Approach Used:**

Data wranggling was first done on the data. Inspection of the data was carried out to ensure that all null values were replaced. A new databse was created and a table was created and data was inserted into it.

A new column COGS (cost of goods sold) was created for the purpose of the analysis.

COGS = sales_volume * price

**Questions Answered**

1. How many unique product_positions do we have?
2. How many unique Terms are in the data?
3. How many unique sections are there?
4. What is the fastest selling sections?
5. What is the fatsest selling term?
6. Total revenue generated.
7. Average quantity of goods sold.
8. Revenue by sections.
9. Revenue by terms.
10. Revenue by the name_of_products.

**Code**

For the code check ZARA SALES DATA.sql file




