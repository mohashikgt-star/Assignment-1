# Assignment-1
Assignment 1: Data Exploration
What is the total price of all products in the dataset?
=SUM(D2:D35)
How many products are there in the dataset?
=COUNTA(D2:D35)
Calculate the average price of the products.
=AVERAGE(D2:D35)
Determine the minimum price among all products.
=MIN(D2:D35)
Find the maximum price among all products.
=MAX(D2:D35)
Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.
=IF(D2>=500,"HIGH PRICE","STANDARD PRICE")
Calculate the total price for products in the 'Electronics' category using the SUMIF function.
=SUMIF(F2:F35,"ELECTRONICS",D2:D35)
 Determine the count of products with a price less than $100 using the COUNTIF function.
 =COUNTIF(D2:D35,"<100")
