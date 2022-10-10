# covid19dashboard
Covid-19 swept over the globe in dramatic fashion, and almost as dramatic was the policy response felt by every nation and by every population. Here in the U.S. we had one of the worst public opinons to what was a health security response. In this project I dive into the data to see what countries faired better than others and how vaccinations have made an impact.

## Topic
Our World In Data - the Covid Dataset provides a great source of data to begin this analysis. The focus of this project is to look at time series data to determine which countries had the most success and which had the least. I look at number of deaths, global figures, vaccination status by nation and by income. 

## Roadmap

1. Extract, Transform, and Load
    - Pull dataset from Our World in Data
    - Sort and transform data in Pandas
    - import dataframes into SQL Postgres Database
2. Query SQL Database for subsets
    - Get aggregate dataset
    - Get vaccination status by nation
    - Get List of highest death count countries
    - Get vaccination status by income
3. Design Tableau dashboard
    - Top worst countries with highest death count
    - Time parameter
    - World metrics
    - Map with vaccination status
    - Bar graph of vaccination status by income

## Tableau Dashboard

![screenshot](/covid19vacc.gif "Covid-19 Vaccinations Dashboard")

[View Dashboard in Tableau Public](https://public.tableau.com/views/Book1_16627808205440/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)