# Bezen-Assignment

#### Attached is a CSV file which has the following details about products from various ecommerce sites. 
##### ● UUID (Primary Key) 
##### ● Price (String) 
##### ● Price_unfiltered (String) 
##### ● Product Type 
##### ● Category 
##### ● Level 1 -> This is just a classification of a product. 

# Task

#### Use the database to find the following results from this data
##### 1. Products without prices 
##### 2. Count of products without prices and with prices in each Product Type, Category, Level 1 
##### 3. Correct Product Prices in the correct format (eg: $56) wherever possible and separate them into currency and value columns. 
##### 4. List out the categories with average price of product. 

# Code 

##### 1. Importing Libraries
##### 2. Import Dataset
##### 3. Check all values which are null in the dataset
##### 4. Created a heatmap depicting the null values in the dataset
##### 5. Counting the frequency of distinct values from each column
##### 6. Some Visualization
##### 7. Creating dataset without price as to display Products without price.
##### 8. Displaying Products which doesn't contain price or price as NA
##### 9. Count of products without and with prices in each Product Type, Category, Level 1
    Total Count = Products without Price + Products with Price
##### 10. Correct Product Prices in the correct format (eg: $56)
##### 11. Splitting Price column into currency and value columns. 
##### 12. Replacing nan values with 0 in Dataset containing Price, Value and Category
##### 13. Finding Categories with average price of product using formula:
    Average Price = Sum(Individual Price)/Total No. of Product
