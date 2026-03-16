PRACTICAL-5
Definition- this practical involves cleaning , transforming and analyzing sales and order data from multiple tables in Power BI .  the goal is to create calculated column , merge tables handle null and inconsisent data and generate visualization.

Outcomes / learning- learned advanced Power Bi data  preparation , including managing relationship between table ,data cleaning , column transformation , and creating calculated metrices like “ Total Amount” and “Final Amount”. 

Required tools- Power Bi Desktop( including Power query editor , DAX , relationships and repoet view.).

Working- imported three tables (northwide orders, order details) into power bi . cleaned data by removing blank and duplicates,replaced null region values and standardized column formats. Created calculated column “ Total  amount” and “Final Amount”, established relationship between datsets.
Dataset Review
  
The dataset consist the orders , customer , and product details from shipping and sales environment , featuring columns like order id ,  order and shipped date , region ,product price, quantity, discount and final amounts.
STEP-1: Importing dataset directly in Power bi
Imported the “ Northwide order” , “Northwide Order Details”  data  in Power Bi using “ Get Data” option.
 
STEP-2: Performing transformation(both datasets)
Used Power Bi query editor to transform the dataset i.e.;removed blank rows , duplicate rows and changed datatypes and also lowercasted  the text.
 
STEP-3:Replace value  with (not known)
Replaced “” with “ not known” of the column ship region by clicking the replace value option  in power query editor









STEP-4; Adding custom column
Open the Power query editor – go to add column and then go to custom column – named ‘Final  Amount” which is equal to-[total amount ]*1-[discount].
 
STEP-5: Performing Visualization







1-	Creating a bar chart showing the count of “Final Amount” by ship_country allowing analysis of sales distribution across country.
2-	Added a bar chart comparing the sum of “ Total Amount” for different ship_countries, which highlights the effect of discounts and help compare revenue before and after discounts by region.
3-	Built a bar chart to visualize the average freight charge by ship_via , enabling evaluation of cost efficiency among different shipping methods.
4-	Included a bar chart showing the number of unique customers  (customer_id) by ship_country, providing insights into customer distribution anf engagement per country.



