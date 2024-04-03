SUPERSTORE SALES POWER BI PROJECT SUMMARY 

Steps followed:

1)Data Cleaning:

• Imported the “Superstore” file from excel into Power BI using “Get data” 
button.

• Transformed the data on Power Query Editor.

• Removed all the null and empty values, changed the datatypes as per the 
data in columns.

• Split the address column into city, state, country, pin code.

2)Data Modelling:

• Created Dimension tables Products, Order Details and Customers from Orders table, 
fact table being Orders table.

• Removed duplicates from the Dimension tables.

• Established the one-to-many relationships between them with fact table in model 
view.

3)Data Analysis:

• Created a new column “Sales” for each quantity with price per each.

• Visualised it using card.

• Created another column “Cart Value” categorising the sales into Low, medium, high 
and very high.

• Created another column “Delivery days” to see difference between ordered and 
shipped dates.

• Calculated average number of days it takes to ship the goods.

• Calculated measures like “Low” category’s products with >= 50% discount, YTD sales, 
YoY growth, Discounted sales using appropriate DAX expressions.

• Visualised through pie, line, column charts and matrix visualisation.

• Applied Slicers as Years, so that for every visualisation, year wise analysis can be seen 
for more clarity.

4)Insights gained:

• Sum of sales grew by every year from 2014 to 2017.
Total Sales "Low"sales-50% Discount Peak sales month
2014 470.64k 3.59k 9
2015 483.68k 3.05k 9
2016 627.23k 3.73k 11
2017 750.47k 3.75k 12
 
 
• Across all 4 Ship Mode, Average Delivery Days ranged from 0.03 to 5.05.

• At 5.05, Standard Class had the highest Average Delivery Days and was 15,852.71% higher 
than Same Day, which had the lowest Average Delivery Days at 0.03.

• Throughout the 4 years the sum of sales is 2.33M.

• YoY Growth and Sales YTD trended up, resulting in a 430.07% increase between January 2014
and December 2017.

• Sales YTD started trending up on August 2017, rising by 37.66% (23,828.76) in 4 months.

• Sales YTD jumped from 63,272.12 to 87,100.87 during its steepest incline between August 
2017 and December 2017.

Total Sales "Low"sales-50% Discount Peak sales month
Suggestions:

• Majority share of sales in from “Low” cart value, so business should target 
them and try to give more discounts to increase their sales.

• Every year end the sales peak, so it is best to leverage it.

• On an average the Delivery days is majorly 5, so try to shorten the period.

Conclusion:

Finished the project by carefully implementing all the necessary steps, drawn 
some good and useful insights through visualisations and made reports.
