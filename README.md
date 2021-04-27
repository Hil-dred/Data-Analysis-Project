

# Project Title
Analysis of store branches of a Supermarket across 3 geopolitical zones; 
* South-West (Lagos)
* North-Central (Abuja)
* South-South (Port-Harcourt)


# Project Steps
* Required python modules and libraries required for the analysis were imported in jupyter notebook
* All three csv files, containing sales data for the 3 branches were concatenated into one csv file
* The data from the resulting CSV file was explored to understand the dataset using: 
	* shape method
	* info() function
	* columns method
* Descriptive statistics was carried out on the dataset using the describe() function
* The pd.to_datetime() function was applied on the date and time columns for datatype conversion
* Components of the date and time columns were extracted using the datetime module	 
* To further understand the data, the number and values of unique items in each categorical column, was obtained using nunique() and unique() functions
* The aggregate sum and mean of each column in the dataframe were generated, grouping by the city column and the branch with the highest gross income was extracted
* Analysis data was vizualised to show: 
	* Highest number of branch sales
	* Highest and lowest product line sold
	* Most used payment channel per product line


# Insights
* Customers purchased an average of 5 products on each patronage
* The cheapest item in all stores is about 3,630 naira while the most expensive is about 40,000 naira
* Customer satisfaction across all stores is above average
* The branch with the highest generated income was branch C (Port-harcourt)
* Individually, the product line most sold was: 
	* Branch A (Lagos) - Home and lifestyle
	* Branch B (Abuja) - Fashion accessories
	* Branch C (Port-harcourt) - Food and beverages
* Cummulatively, the product line most sold was Fashion accessories


# Executive Summary
* The executive summary for this analysis can be found in this repo
