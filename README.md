# MGT 4250 Spring 2024 Course Project
Author: Esteban Penagos (epenagos@elon.edu)

## Project description: Section 1
### Questions of interest
- Which goods are sold the most through E-Commerce?
- What are the countries with the most E-Commerce activity? 
- By having data from 2018 and 2019, did E-Commerce grow in that year and if it did by how much?
### Importance statement 
These questions are important because
1. It will let companies check the amount of goods and services being sold online. 
2. They will also be able to know what products are more likely to be sold online rather than in the store and they would be able to concentrate and do marketing accordingly.  
3. The results could give us a good idea of the potential upcoming year growth.


## Link that will take you to Tableau Public
This link will take you to Tableau Public where wou will be able to see two dashboards with my visualizations for the class project of MGT 4250 at Elon University.
https://public.tableau.com/app/profile/esteban.penagos/vizzes

# Data Description and Upload: Section 2
When accecing the data which is in an excel file, you will need to go to Github and in my respository access the file called "sales Transaction v.4a.xlsx. That document will give you access to an excel workbook with all the raw data used to create the visulizations.
In order to find this data I went into keggle and found data regarding E-commerce. the following link will take you to the page where i got the data from and I scrolled down to where it says Sales Transaction v.4a.csv, and i downloaded that data frame. 
https://www.kaggle.com/datasets/gabrielramos87/an-online-shop-business

## Data Types and Descriptions: 
1. For all visualizations, there are different data types that were used. For the visualization "Quantity sold by Country", we are using the Country into rows which is a string, and we are pairing it with the sum of quantity which is a number.
2. For the visualization "#Products sold", we are using the sum of quantity again and we are mathing is with product name on the rows which is a string in order to make a table.
3. For the third visualization in the first Dashboard, "Sum of quantity sold change Q2019" we are using the sum of quantity which is a number as a whole in the rows, and we are pairing it with Date down to the quaterly date to show the different quarters of the year. The type of this data is Date.
4. The first visualization for the second Dashboard called "Country quantity sold" I am using the country data for the label which is a string, and pairing it with the sum of the quantity. I am making a tree map for this visualization.
5. For "Product sold by Country" I am putting Country and Product name which are both strings into the rows and the Sum of the quantity for the labels.

# Interpreting Visualizations: Section 3
For Dashboard 1 there are three visualizations:
1. Quantity sold by Country gives us an understanding to see what countries have the highest e-commerce sales. We can see the country and the quantity of products sold in each of them. By doing this, we can see what countries, and even companies have the best services and technology for e-commerce. It can also tell us if people in certain regions are more incline to buy products through e-commerce. Looking at the table, which we gave colors to determine the quantity, blue being higher and dark red being the lowest, we see that the Uniked Kingdom has a clear lead on the e-commerce world. We aslo see that in the top 10 countries, 8 of them are in Europe. That makes us think that maybe people in Europe are more incline to e-commerce? Maybe the platform and technology in European companies is better for e-commerce?
2. The second visualization #Products sold helps us to know whic products are sold the most through e-commerce. Based on the data and the visualization we see that Popcorn Holders is the product that is sold the most with 56,450 pieces sold. The table is filtered so in top are the items with the most units sold. This can help compnaies know what people want to buy through e-commerce and it can help them with inventory issues and sales forecasting.
3. The third visualization for the first Dashboard is Sum of quantity sold change Q2019, which shows us the amount of products sold in each quarter in 2019 through e-commerce. This is a great way to see if the e-commerce sales are increasing or decreasing. By knowing this, we are able to predict future years demand, and companies are able to shift their production accordignly. The visualization is telling us that the quantity of products is contantly increasing and the e-commerce business is growing.

For Dashboard 2 there are two visualizations which go hand in hand: 
1. Country quantity sold is helping us know with a tree map which are the countries with the highest quantity of products sold. By applying a filter into the tree map so everytime we chose a different country the other visualization loads for that specific country helps us know what are the products that are sold the most in that specific place. That is a good measure for companies to see what products people in their specific country like to purchase the most through e-commerce. They might be able to do better marketing for that specific product.
2. For the second visualization, Product sold by Country, we have a table with the country, the product name that each country sells, on top being the highest quantity, and the number amount of the product. I placed a filter so when we chose a country, the table filters that country and we are able to see the product and the number amount sold for that specific product. Like this we are able to see which is the top product for every country and how much they have sold of that product.

With all visualizations woking together, we are able to answer all questions and go beyond them. Companies are able to make predictions based on next quarter/year demand for each product they sell and they are able to see it from an e-commerce perspective.

# Discussion & Summary: Section 4


[Elon University(https://elon.edu)]
<img width="290" alt="Screenshot 2024-05-02 at 2 53 38 PM" src="https://github.com/epenagosl/mgt4250spring2024/assets/168772735/53de15c1-7bb5-47b5-9136-12a9079601d7">

```python
import pandas as pd
```
