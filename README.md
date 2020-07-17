# pymaceuticals-challenge
Matplotlib Bootcampspot Homework


# Background
What good is data without a good plot to tell the story?
So, let's take what you've learned about Python Matplotlib and apply it to a real-world situation and dataset:
While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.


# Instructions
  - Your tasks are to do the following:
  - Before beginning the analysis, check the data for duplicate mice and remove any data associated with that mouse ID.
  - Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
  - Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows  the number of mice per time point for each treatment regimen throughout the  course of the study.
  - NOTE: These plots should look identical.
  - Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
  - NOTE: These plots should look identical.
  - Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
  - Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
  - Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.
  - Generate a line plot of time point versus tumor volume for a single mouse treated with Capomulin.
  - Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
  - Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
  - Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

# Analytical Observations

  - Capomulin treatment for mouse B128 shows that the drug regimen was significantly effective over 45 days. However, after a steady decline for 38 days, the mouse's tumor volume started to increase. Although the drug regimen show's promise of working, additional time may provide a more clear answer.
  
  - The Boxplot for the final tumor of each mouse across four drug regimens show a large advantage for Capomulin and Ramicane treatments with relatively similar outcomes.
    
  - The linear regression model shows the mouse weight has a strong correlation (R-squared of 0.84) with the average tumor volume. This data suggests that although the final tumor volume has reduced, the mouse's weight should also be observed to have a full understanding of their recovery. 
  
  - Final Jupyter Notebook submission is under the filename: pymaceuticals_starter-checkpoint.ipynb

