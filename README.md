# 2019 Stack Overflow Developer Survey Analysis with IBM Cognos
## Data Collection
Downloaded dataset from [Stack Overflow's 2019 Developer Survey](https://insights.stackoverflow.com/survey) and selected a randomised subset containing around 1/10th of the original data.

## Data Cleaning
Used a pandas funciton to drop duplicates, imputed missing values, normalized compensation data to show anual compensation across respondents.

## Data Exploration
Graphed the distribution curve for the ConvertedComp column and found there is a positively skewed distribution. Calculated the median ConvertedComp to be $57,745. Discovered 879 outliers in the ConvertedComp column and removed them. Found the correlation between Age and all other numerical variables.

## Data Visualization with Python
Used sqlite3 to query and connect to database for visualizations. Utilized pandas library to visualize distribution, composition, relationships, and comparison of data

## IBM Cognos
Created a dashboard with 3 tabs: Current Technology Usage, Future Technology Trend, and Demographics. You can view the full dashboard [here](https://dataplatform.cloud.ibm.com/dashboards/299374d0-b380-43c9-b1f4-65d43e60e0c3/view/731cf70b1d822ce01fdeeee407cc2b022e3f275bb6bb810580d67b495e687497a86010c3c87d425ede165666a5ea165ecc).

###### Current Technology Usage
Visualized the top 10 programming languages, databases, and webframes as well as the platforms used by the respondents.

###### Future Technology Trend
Visualized the top 10 desired programming languages, databases, and webframes as well as the platforms respondents want to learn next year.

###### Demographics
Graphed respondent's age, gender, education level, and country. Added user interactivity by using a filter on the different genders.

## Findings 
* Javascript and HTML/CSS continiue to be the most popular programming langauges.
* Python, the fastest-growing major programming language, is still rising in the ranks of programming languages.
* Most respondents were men between the ages of 23 to 31 with at least a Bachelor's degree. 
* Many respondents live in the US or India.
* Nonrelational databases such as MongoDB are increasing in popularity.
* Linux is the preferred platform.
