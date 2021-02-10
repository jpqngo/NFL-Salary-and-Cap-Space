# NFL-Salary-and-Cap-Space
* Created a linear regression model to calculate win percentage of an NFL team using player salaries and a team's active spending
* Scraped 3 seasons of NFL position salary and team cap space from *Spotrac*
* Cleaned and prepared data for modeling 

## Code and Resources Used 
* **RStudio**
* **Packages:** tidyverse, readxl, ggplot2, gridExtra
* **Scrapper Video Guide:** https://www.youtube.com/watch?v=WeuAiqWlcu0&list=PL5yaEpfLggUQxIHFOW4dtX9EUSRbUS4-x&index=17

### Cleaning the Data 
* Removed unneeded symbols in observations 
* Simplified titles and changed data type of observations into numerics 
* Added Year Variable to data and removed Rank variable 
* Removed average row (3) in data 
* Combined the data for all 3 seasons 
* Merged the team data and positional data together group by Team Name and Year
* Made data consistent by changing "Redskins" to "Washington Football Team"
* Removed identical variables: Active and Total are the same

#### EDA 
* Looked at summary statistics to see averages across the NFL 
* Created Univariate plots to look at distribution 
* Created Bivariate plots to find correlation 

##### Linear Regression Model 
* Created linear regression model using statistically significant variables
* Compared residuals to see how the data fits 

###### Implementation 
Teams can use the model to create realistic goals for their teams coming into the season. For example, a team that spends less money may make it their goal to rebuild and find new talent throughout the season. On the other hand, a team that spends a lot of money may make it their goal to reach the playoffs or win a Superbowl. The model may also be useful in off season planning by prioritizing money on statistically significant positions. One course of action is to spend less money on wide receivers and focus spending money on the defensive line. The model is far from perfect, but it still has some useful aspects to it.
