# Global Superstore Analysis

# OBJECTIVES

The aim of this analysis is to examine a Global Superstore’s data over a 4-year period, ranging from 2011 to 2014, across 147 countries. Through this analysis, I aimed to identify the array of products sold across primary categories such as Furniture, Office Supplies, and Technology, including subcategories like chairs, smartphones, staples, binders, and more. This thorough examination serves as a foundation for making strategic decisions aimed at enhancing performance and maximizing profitability.

# DATA SOURCE

The data used for the project is a secondary data
https://docs.google.com/spreadsheets/d/1jHUmgAMFSxeZUBT4Kd0HDOXpxV3rFJOj/edit?usp=share_link&ouid=102731908679789782364&rtpof=true&sd=true

# DATA CLEANING AND TRANSFORMATION
 Power Query editor was used for the cleaning and PowerBI was used for the visualization.

### The data consist of three(3) tables: 

     For the People table:

&#8226; Used first row as headers

&#8226; Removed nulls

     For the Returns table:

&#8226; Used first row as headers

&#8226; Removed duplicates

&#8226; Deleted an empty column

    For the Orders table:

&#8226; Deleted an empty column 

&#8226; Removed duplicates.

### ADDITIONAL TABLE
Created an additional table for my country, city and state.

# DATA MODELLING
Linked/created a relationship between the four (4) tables: the people table, return table, order table and country table.

# DAX

Created a Dax formula for:
&#8226; Sum of sales

&#8226; Sum of profit

&#8226; Average Shipping

&#8226; Average profit

&#8226; Average discount

# INSIGHTS

The total sales from 2011 - 2014 is 9 million, the total profit 1 million, from 147 countries.

|    |2011|2012|2013|2014|
|----|----|----|----|----|
|Sales|2 million|2 million|3 million|3 million|
|Profit|184k|227k|309k|370k|
|Country|133|129|137|138|

From the table above we can deduce that the higher the country that Furniture, Office supplies and Technologies were sold the higher the sales and profit.

&#8226; The top 5 countries with the highest sales are the United States with 2 million, Australia with 1 million, France with 1 million, Mexico with less than 1 million.

&#8226; The top 5 countries with the highest profit are the United States with 222k, China with 110k, India with 96k, United Kingdom with 85k  and Australia with 80k.

|    |Furniture|Office Supplies |Technology|
|----|----|----|----|
|Sales|3 million|2 million|4 million|
|Profit|217k|330k|543k|
|Country|130|140|138|

From the above table we understand that Technology appliances had higher sales, profit.

&#8226; December made the highest sales and profit , for profit it made 1, 218,596 million and for sales 132, 462 thousand.


















 

