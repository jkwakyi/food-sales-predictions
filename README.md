# food-sales-predictions
Sales forecast for food items sold at various franchises under one company.

I wanted to utilize the dataframe in the best way possible so I grouped multiple datapoints together inorder to produce a visualizations that would help me interpret the data and ultimatly find a machine learning model that would forecast sales.
I used outlet 27 as my baseline outlet because it outperformed every other outlet in sales. 
outlet 27 is a medium sized Supermarket type 3 with average Item visibility and the third lowest MRP
My heatmap visualized that those 4 features correlated the most with item outlet sales so I verified that against outlet 27's data.
Multiple boxblots were used to verify that outlet 27 was included in the features that correlated the most with item oulet sales and that proved to be true

I used the regression tree model with a maximum depth of 5 because it produced the most accurate results with a 60%/59% train vs. test split.
I would recommend using the regression tree model due to its accuracy in predicting item outlet sales. 
I would also recommend any future outlets to be a medium supermarket type 3 while maintaining 6% visibility of all items for sale and keeping the MRP around $139 for the products purchased from the manufacturer. 

Results were delivered to the company's main sales headquarters. contract complete.
