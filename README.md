# zepto-SQL-data-analysis-project

The goal is to simulate how actual data analysts in the e-commerce or retail industries work behind the scenes to use SQL to:<br>
-Set up a messy, real-world e-commerce inventory database<br>
-Perform Exploratory Data Analysis (EDA) to explore product categories, availability, and pricing inconsistencies<br>
-Implement Data Cleaning to handle null values, remove invalid entries, and convert pricing from paise to rupees<br>
-Write business-driven SQL queries to derive insights around pricing, inventory, stock availability, revenue and more

#### Dataset Overview
The dataset was sourced from Kaggle and was originally scraped from Zepto’s official product listings. It mimics what you’d typically encounter in a real-world e-commerce inventory system.<br>

#### Columns:

-sku_id: Unique identifier for each product entry (Synthetic Primary Key)<br>
-name: Product name as it appears on the app<br>
-category: Product category like Fruits, Snacks, Beverages, etc.<br>
-mrp: Maximum Retail Price (originally in paise, converted to ₹)<br>
-discountPercent: Discount applied on MRP<br>
-discountedSellingPrice: Final price after discount (also converted to ₹)<br>
-availableQuantity: Units available in inventory<br>
-weightInGms: Product weight in grams<br>
-outOfStock: Boolean flag indicating stock availability<br>
-quantity: Number of units per package (mixed with grams for loose produce)

#### Business Insights:

-Found top 10 best-value products based on discount percentage<br>
-Identified high-MRP products that are currently out of stock<br>
-Estimated potential revenue for each product category<br>
-Filtered expensive products (MRP > ₹500) with minimal discount<br>
-Ranked top 5 categories offering highest average discounts<br>
-Calculated price per gram to identify value-for-money products<br>
-Grouped products based on weight into Low, Medium, and Bulk categories<br>
-Measured total inventory weight per product category
