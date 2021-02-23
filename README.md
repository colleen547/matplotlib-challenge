# matplotlib-challenge
***The Power of Plots***
<div style="text-align:center"><img src="static/images/labmouse.jfif" width="1000" height="300"/></div>
BACKGROUND<br>
Pymaceuticals Inc., is a burgeoning pharmaceutical company based out of San Diego specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In a recent animal study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

Using complete data from this study, tables and figures were generated for a technical report and to create a top-level summary of the study results.<br>

DETAILS<br>
Your tasks are to do the following:


Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID (i.e., exclude that mouse from the analysis).


Use the cleaned data for the remaining steps.


Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.


Generate a bar plot using both Pandas' DataFrame.plot() and Matplotlib's pyplot that shows  the number of total mice for each treatment regimen throughout the course of the study.


NOTE: These plots should look identical.



Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.


NOTE: These plots should look identical.



Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.


Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.


Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. timepoint for that mouse.


Generate a scatter plot of average tumor volume vs. mouse weight for the Capomulin treatment regimen.


Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.


Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.


Here are some final considerations:


You must use proper labeling of your plots, to include properties such as: plot titles, axis labels, legend labels, x-axis and y-axis limits, etc.
