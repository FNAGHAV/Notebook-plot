# Notebook-plot
Challenge 5
Analysis Report

Section 1: Prepare the Data:
In this initial step, we loaded data from two CSV files into Pandas dataframes and merged them using the "Mouse ID" column. We made sure to remove any duplicate entries for mouse ID "g989" to maintain data accuracy.
Section 2: Generate Summary Statistics:
Next, we calculated essential statistics such as mean, median, variance, standard deviation, and standard error of the mean to understand the distribution of tumor volumes across different drug regimens. We utilized both groupby operations and aggregate functions for a thorough analysis.
Section 3: Create Bar Charts and Pie Charts:
To visualize the data, we created bar charts to show the observed timepoints for each drug regimen and pie charts to illustrate the gender distribution among the mice. Notably, "Capomulin" and "Ramicane" stood out with the highest observed mouse timepoints.
Section 4: Calculate Quartiles, Find Outliers, and Create Box Plots:
Digging deeper, we examined the last timepoint data for specific drug regimens, calculated quartiles, identified outliers, and presented the information using box plots. 
Individual Mouse Analysis:
Zooming in on specific mouse data under the "Capomulin" treatment, we analyzed the tumor volume trajectory over time for mouse "l509." Additionally, we explored the correlation between average tumor volume and average weight for "Capomulin"-treated mice, revealing a strong positive correlation (0.84). A regression equation (y=0.95x+21.55) provided predictive insights.
In the final visual exploration, a scatter plot with a linear regression line illustrated the correlation between weight and tumor volume, offering a comprehensive understanding of their relationship.
This detailed analysis provides valuable insights into tumor volume distribution, the effectiveness of drug regimens, and correlations between weight and tumor volume for the studied mice. 
