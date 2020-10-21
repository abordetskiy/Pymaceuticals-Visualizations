# Pymaceuticals - The Power of Plots

### This project involves imports of multiple CSV files, and Python Pandas and MatPlotlib libraries to run analysis and data visualization on a drug trial conducted on mice.

The Analysis begins by showing visually that the Trial parameters were equally distributed among drug regimen and gender, providing confidence in the results. Via the quartile visualization, it is easy to see which drugs seem to be effective in reducing tumor volume. 

It then provides detailed statistical analysis demonstrating the effectiveness of a specific drug regimen, showing both the tumor volume over time in a single, random mouse participant. 

The final calculation done on the specific drug regimen includes both a Pearson's correlation analysis and a linear regression drawn directly onto a scatterplot.  

### All these data tables and visualizations are outputted directly in pymaceuticals_main.ipynb and detailed analysis of observable trends are included.

1a: From a first glance at the BoxPlot - it seems that Capomulin and Ramicane groups showed 
a much lower distribution of Final Tumor Volume - suggesting these drugs may have a larger effect
1b: Referring to the Summary Statistics chart, both Capomulin and Ramicane also had significantly
lower average tumor volume while also having the least variance and standard deviations. 
This also suggests these drugs may have a larger effect with a tighter cluster of lower volume tumors.

2: Looking at the Bar and Pie charts - the obervation to be made is that the demographics are evenly
distributed among the sample. This already suggests that the population should behave relatively 
normally, save for the variables that are being altered. In short, it supports the validity of the experimental groups
and strengthens trust in the results.


3: The correlation coefficient of .84 shows a strong correlation between the weight of the mouse
and the average tumor volume. This makes sense as heavier mice would have larger general size and
structure, meaning that larger tumors may be "easier" for heavier mice to grow. It would be interesting to see if the
for the other drug regimens was similariy correlated, or if there was a 
different relationship between mouse weight and average tumor volume