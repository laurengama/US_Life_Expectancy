# US Life Expectancy
Lauren Gama, Conor Healy, Myke London, Kevin Menz, Angela Spirou

## Summary

#### Description
Our data science group project explores multiple factors such as gender, income, state of residence, state’s uninsured population, and access to quality health care related to life expectancy (LE) in the US.

#### Motivation
For our first group project, we were guided to the [Health Inequality Project]( INSERT LINK) on life expectancy in the US. As soon as we saw the extent of the information available, we wanted to pull findings and share some of the factors that influence life expectancy. 

#### Result
Using python, we were able to run statistical analyses and create heatmaps to answer the following questions: 
* Q1. Are there differences in national LE by gender?
* Q2. Are there differences in national LE by income?
* Q3. Which states have the highest/lowest LE?
* Q4. Is LE affected by the percent of the state’s uninsured population, percent of the state’s African-American population, and percent of the state’s Hispanic population?
* Q5. Are there differences in state LE by access to quality health care?

#### Team Efforts
Each member of the team tackled a different question. Angela answered Q1, Kevin answered Q3, Myke answered Q4, Conor answered Q5, and I answered Q2. 

#### Individual Responsibilities
* Use the Online Data Table 2: National by-year life expectancy estimates for men and women, by income percentile CSV file.
* Remove all columns other than gender, household income percentile, year, and race-adjusted life expectancy.
* Use bins to categorize the income percentiles into quartiles.
* Create dataframes for each quartile using the loc function.
* Group the new dataframes by year using the mean of the race-adjusted life expectancy.
* Plot these four groups using a line graph with the year on the x-axis and LE on the y-axis and one line for each income quartile.
* Plot national female LE over time and national male LE over time.
* Plot the difference in LE by income using a boxplot.
* Run an ANOVA revealing that the differences between mean LE for each quartile was significant (p < 0.001).
* Perform t-tests on Q1 male and female LE as well as Q4 male and female LE to see whether differences were significant at either end of the income spectrum. Both t-tests were in fact significant, with p-values well below 0.001.

#### Challenges
With such a rich dataset, it was difficult for our team to limit ourselves and decide exactly what questions we wanted to answer. However, we wanted to be able to tell a story with our presentation, so I helped guide our team members to each focus on one question they found most interesting. This kept our project structured, feasible, and cohesive.

#### Improvements
As this was our first project, there is a lot that can be added with all that we have learned since then. I would be most interested in using Tableau to enhance our findings and do some further exploration with the data.

