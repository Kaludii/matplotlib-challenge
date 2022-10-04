# matplotlib-challenge

### Generated Summary Statistics

Created a DataFrame of summary statistics. Remember, there is more than one method to produce the results you're after, so the method you use is less important than the result.

Summary statistics includes:

* A row for each drug regimen. These regimen names should be contained in the index column.

* A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.

### Created Bar Charts and a Pie Charts

1. Generated two bar plots. Both plots are identical and show the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

    * Created the first bar plot by using Pandas's `DataFrame.plot()` method.

    * Created the second bar plot by using Matplotlib's `pyplot` methods.

2. Generated two pie plots. Both plots should be identical and show the distribution of female or male mice in the study.

    * Created the first pie plot by using both Pandas's `DataFrame.plot()`.

    * Created the second pie plot by using Matplotlib's `pyplot` methods.

### Calculated Quartiles, Find Outliers, and Created a Box Plot 

1. Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR and determine if there are any potential outliers across all four treatment regimens.

    * Created a grouped DataFrame that shows the last (greatest) time point for each mouse. Merge this grouped DataFrame with the original cleaned DataFrame.

    * Created a list that holds the treatment names, as well as a second, empty list to hold the tumor volume data.

    * Looped through each drug in the treatment list, locating the rows in the merged DataFrame that correspond to each treatment. Appended the resulting final tumor volumes for each drug to the empty list. 

    * Determined outliers by using the upper and lower bounds, and then print the results.
    
2. Using Matplotlib, generated a box plot of the final tumor volume for all four treatment regimens. Highlight any potential outliers in the plot by changing their color and style.

### Created a Line Plot and a Scatter Plot

1. Selected a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

2. Generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

### Calculated Correlation and Regression

1. Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. 

2. Ploted the linear regression model on top of the previous scatter plot.
