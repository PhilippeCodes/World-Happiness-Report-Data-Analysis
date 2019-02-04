# World-Happiness-Report-Data-Analysis
Analyzing the World Happiness Report dataset as Part of The EPFL Applied Machine Learning Course (Project 1).
The purpose of this project is to exercise and demonstrate acquired abilities.
Should the person who is looking at this analysis have any questions or suggestions, do not hesitate to contact me.

## The Data
Our dataset is the 2017 World Happiness Report published by the United Nations Sustainable Development Solutions Network. This data was collected by the Gallup World Poll, using a set of surveys from more than 160 countries in over 140 languages. The surveys aim to analyze data from hundreds of thousands of individuals and investigate the ways in which elements of people’s working lives drive their wellbeing.

Each country is given a happiness score that is the sum of scores from the following 7 criteria:

GDP per capita
healthy years of life expectancy, social support (as measured by having someone to count on in times of trouble),
trust (as measured by a perceived absence of corruption in government and business)
perceived freedom to make life decisions
generosity (as measured by recent donations)
dystopia (benchmark country corresponding to the lowest possible values in each of the criteria)
The countries are then ranked from most happy to least happy.

Additionally, the report contains information about job satisfaction in each country.

## Tasks performed:

### A. Importing, cleaning and numerical summaries
1. Download the data set data.csv from the Resources tab.
2. Import the data as a pandas DataFrame.
3. Check the number of observations.
4. Obtain the column headings.
5. Check the data type for each column.
6. Check if there are any missing values.
7. If necessary remove any observations to ensure that there are no missing values and the values in each column are of the same data type.
8. Obtain the mean, minimum and maximum value for each column containing numerical data.
9. List the 10 happiest countries.
10. List the 10 least happy countries.

### B. Indexing and grouping 
1. Use the column 'Region' to create a separate DataFrame containing the data points from each of the six regions: North America, Latin America, Western Europe, Eastern Europe, Asia Pacific, Africa.
2. Compute the mean happiness score for each region and rank the regions from most happy to least happy.
3. Compute the number of countries in each region that have a happiness score above 6.0.
4. Compute the difference between the maximum and minimum happiness score for each region. Which region has the largest range of happiness scores?

### C. Bar plot of the Happiness Score
1. Obtain a horizontal bar plot of the Happiness Score of the top 10 countries. Your bar chart should have the names of the countries are listed vertically along the y-axis and the x-axis should have labels for each number from 
0 to 8. Ensure that the chart has an appropriate title and labels.
2. You will now modify the bar chart you obtained in step 1 to turn into a stacked bar chart where the overall happiness score is divided into the seven parts corresponding to the columns:
- Economy
- Family
- Health
- Freedom
- Generosity
- Corruption
- Dystopia Choose a distinct color for each category and include an appropriate legend with your chart.
3. Obtain the same stacked horizontal bar chart as in step 2 but this time instead of the top 10 countries consider all countries from the region Africa.

### D. Histogram of Job Satisfaction
1. Obtain a histogram of the Job Satisfaction using the following categories:
- 40%-50%
- 50%-60%
- 60%-70%
- 70%-80%
- 80%-90%
- 90%-100%

### E. Pairwise Scatter plots
1. Obtain scatter plots of the Happiness Score versus each of the other variables. Your plots should be displayed as multiple plots table and obtained with one command as supposed to separate commands for each plot.

### F. Correlation
1. Obtain the correlation between the Happiness Score and each of the other variables. Which variable has the highest correlation with the Happiness Score?

### G. Probabilities
1. Compute the probability that randomly selected country with Happiness score over 6.0 is from Western Europe. You will have to use pandas to count the appropriate quantities.

### H. Matrices
1. Define a matrix whose rows correspond to countries and the columns to the regions. Fill in the matrix with 
0/1 values where entry (i,j) is a 1 if the country in row i
is in the region in column jand a 0 otherwise.
