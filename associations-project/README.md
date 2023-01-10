# Variable Associations

## There are two datasets explored in this project:

1. Narcissistic Personality Inventory (NPI) Responses
2. National Basketball Association (NBA) Trends

## NPI Project walkthrough:

1. Read-in dataset and examine first five rows
2. Select four questions of interest for investigation
3. Wrangle and clean dataset by removing most columns and renaming remaining ones
4. Replace numerical tabular data with equivalent strings (i.e. 1 = 'yes', 2 = 'no')
5. Remove rows containing data that interferes with binary data
6. Remainder of project investigates association (or lack thereof) of categorical variables

### Tools used:

* Observed contingency tables
* Expected contingency tables
* Chi-Square statistic (to establish correlation for categorical variables)

## NBA Trends Project walkthrough:

1. Read-in dataset and examine first five rows
2. Create two variables representing two different years from the dataset (i.e. 2010 and 2014)
3. For the first year, filter for two different franchises (Knicks and Nets)
4. Calculate the *average difference* for total points scored by each team per game
5. Display overlapping histograms to visualize the spread of each teams' point totals
6. Complete the same tasks (3-5) for the second year
7. Visualize side-by-side boxplots comparing different franchises to their total points scored
8. Determine if there is an association between 'game_location' and 'game_result' using contingency tables and the Chi-Square statistic (categorical variables)
9. Calculate correlation between 'forecast' (franchise odds) and 'point_diff' (difference in total points) using Pearson Correlation and calculating a correlation coefficient (two quantitative variables)
10. Display a scatterplot for both variables to visualize the linear association (should make sense given the correlation coefficient)

### Tools used:

* Mean difference
* Overlapping histograms
* Side-by-side boxplots
* Scatterplots
* Chi-Square statistic (categorical variables)
* Pearson Correlation (quantitative variables)