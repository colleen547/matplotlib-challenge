# matplotlib-challenge
***The Power of Plots***

BACKGROUND<br>
Pymaceuticals Inc., is a burgeoning pharmaceutical company based out of San Diego specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In a recent study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

Using complete data from this study, tables and figures were generated to create a technical report and top-level summary of the study results.<br>
<div align="center"><img src="static/images/scientist.jpg" width="500" height="300"/></div>
DETAILS<br>
The data was cleaned to remove any mouse ID with duplicate time points and used to complete the following steps.<br>

- A summary statistics table was generated consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.<br>

Using using both Pandas `DataFrame.plot()` and Matplotlib's `pyplot`, the following were generated:<br>
- A bar plot to show the number of total mice for each treatment regimen throughout the course of the study.
- A pie plotto show the distribution of female or male mice in the study.<br>

After the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin were calculated, quartiles and IQR were calculated to quantitatively determine if there were any potential outliers across all four treatment regimens.<br>

Using Matplotlib, a box and whisker plot of the final tumor volume was generated for all four treatment regimens and potential outliers in the plot were highlighed by changing their color and style.<br>

Next, a mouse that was treated with Capomulin was selected and a line plot of tumor volume vs. timepoint was generated for that mouse.<br>

A scatter plot of average tumor volume vs. mouse weight for the Capomulin treatment regimen was generated.<br>

Finally, the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment were calculated. And the linear regression model was plotted on top of the previous scatter plot.<br>

Please note the proper use of labeling for each of the plots, including properties such as: plot titles, axis labels, legend labels, x-axis and y-axis limits, etc.
