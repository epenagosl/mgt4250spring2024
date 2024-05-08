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

## Data Types and Descriptions: 
For all visualizations, there are different data types that were used. For the visualization "Quantity sold by Country", we are using the Country into rows which is a string, and we are pairing it with the sum of quantity which is a number. For the visualization "#Products sold", we are using the sum of quantity again and we are mathing is with product name on the rows which is a string in order to make a table. For the third visualization in the first Dashboard, "Sum of price change Q2019" we are using the sum of price which is a number as a decimal in the rows, and we are pairing it with Date down to the quaterly date to show the different quarters of the year. The type of this data is Date. 

[Elon University(https://elon.edu)]
<img width="290" alt="Screenshot 2024-05-02 at 2 53 38 PM" src="https://github.com/epenagosl/mgt4250spring2024/assets/168772735/53de15c1-7bb5-47b5-9136-12a9079601d7">

```python
import pandas as pd
```
