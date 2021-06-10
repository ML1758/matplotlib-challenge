# matplotlib-challenge
matplotlib-challenge Assignment - Milinda 'ML' Liyanage

## Summary

* This program uses two data sets to identify and analyse data of cancer treatment test done mice. 

### The following steps were done: 


* The merged data has 1893 rows.
* The duplicated Mouse ID is g989
* There are 18 records of this duplicated Mouse ID.
* After removing the duplicated Mouse ID entirely, the clean data frame has 1880 rows. As summary 
* A summary statistics data frame is displayed by Drug Regimen by groping method and aggregation method.
* A bar chart  of the Time Point counts of Drug Regimen is displayed using both pandas and pyplot methods.
* A pie chart  of the sex of the mice is displayed using both pandas and pyplot methods.
* A data frame of the final tumour volume of each mouse across four of the treatment regimens,  Capomulin, Ramicane, Infubinol, and Ceftamin, is displayed.


####  The IQR and quantitatively 
  	* •	The lower quartile of tumour volumes is: 40.2201707875
	* •	The upper quartile of tumour volumes is: 50.356470630000004
	* •	The interquartile range of tumour volumes is: 10.136299842500001
	* •	The median of tumour volumes is: 45.0 
	* •	Values below 25.01572102375 could be outliers.
	* •	Values above 65.56092039375001 could be outliers.

* A box plot of the final tumour volume of each mouse across four of the treatment regimens,  Capomulin, Ramicane, Infubinol, and Ceftamin, is displayed.
* A line plot of tumour volume vs. time point for a mouse treated with Capomulin regimen is displayed.
* A scatter plot of average tumour volume vs. mouse weight for the Capomulin regimen is displayed. 
* A leaner regression line on scatter plot is also shown.

## Analysis/Observations of the Data

* Fairly distributed data with a very few outliers
* There is and outlier for Infubinol Drug Regimen as can see from the boxplot.
* For the Capomulin Drug Regimen, it can be see from line chart than as with time the tumour volume decreases.
* The Pearson’s r is very close to 1, therefore, we can say there is a strong correlation between mouse weight and tumour volume for Capomulin regimen.
* The  linear regression line confirms that there is a strong correlation between mouse weight and tumour volume for Capomulin regimen.
* There were duplicated rows which has to removed, this was less 1% of the sample, therefore, does not have impact on the over results.


### Jupyter Notebook

*  [pymaceuticals.ipynb](Pymaceuticals/pymaceuticals.ipynb) 

#### Data Files

* [Source file - Mouse_metadata.csv](Pymaceuticals/Data/Mouse_metadata.csv) 
* [Source file - Study_results.csv ](Pymaceuticals/Data/Study_results.csv) 

#### Output Files

* [File in folder](Pymaceuticals/Images/) 

