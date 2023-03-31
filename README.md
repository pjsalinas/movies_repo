# Microsoft Movies Project

### Repo Contents
- [Exploratory Notebooks]()
- Report Notebook
- Project Presentation
- Project Data
- References
- Project Source Code
- Project Visuals


### Table of Contents
- [Introduction](#introduction)
- [Project Overview](#overview)
- Conda Environment
- [Data](#data)
- Data Preparation
- Results
- Next Steps
- References

## Introduction
This project analyzed the movie industry on behalf of Microsoft Inc., which is considering investing in the movie business. Due to the numerous factors that influence the success of a movie across various platforms, and considering Microsoft's time constraints and pressure, we focused on analyzing a limited number of key parameters to gain insights and generate actionable recommendations for the Microsoft board of directors.

## Overview
Microsoft is exploring the possibility of entering the movie industry using its surplus cash. In 2019, the movie business was valued at $42.2 billion, while the global film industry, including box office and home entertainment revenue, was worth $136 billion in 2018. To assess the viability of such an investment, Microsoft is planning to conduct a thorough analysis of the movie business, focusing on aspects such as profitability and budget. Once the Microsoft board approves the investment, the company will move forward with hiring directors, writers, and actors.

### Conda Environment

## Data
The Microsoft Marketing team provided us with several datasets pertaining to the movie industry. After careful consideration, we selected the two most relevant and reliable datasets. Using these datasets, we were able to evaluate and analyze various types of data such as dates, profits, budgets, and other relevant factors.

## Results
- What are the most profitable movies, and how much to spend on them?
- What are the most common genre?
- What is the best time of the year to release a movie?

### What are the most profitable movies, and how much to spend on them?
![most profitable movies](https://github.com/pjsalinas/movies_repo/blob/main/images/profit_budget_top_25.png)
As we can see the most successful movies have incredible profits and profit margings. Titanic(1997), Avatar, two of the Star Wars saga, and Avengers:Infinity War are the most successful movies in term of profits.

What's happening?
Let's pick up a valid margin that we would like to see on each movie produced. Of all the 3611 profitable movies (profit > $0) 2594 have a profit margin of more than 50%. Meaning, we can be more aggresive in choosing a threshold for the profit margin. The top 25 movies have a median profit margin of 73.27% with a median production budget of $363.750.000. When looking to all profitable movies the profit margin is of 67.53% and a budget of $34.312.500. We choose the median here to describe the data since the mean will be skewed because the data outliners.

Evaluating the data with a profit marging of 75% or greater, and a budget greater than $34.312.500. We found out we still have 499 movies left upon which we can draw some conclusions.

Using a scatter plot to examine the data. We can see that the data poits are more spreadout when comparing profit margin and production budget. The trend line in this case is negative which caution about spending to much money as we might potentially hurt our profit margin. Looking at the hipotesis data, we have a median production budget of $104.078.951 and a median profit marging of 82.94%.

With a Median Production Bugdet $104,078,951, and 
Median Profit Marging 82.94%

![Adjusted Budget versus Profit Margin](https://github.com/pjsalinas/movies_repo/blob/main/images/budget_vs_margin.png)

**Recommendations: Microsoft should make movies with production budgets of $104,078,95 to obtain margins of 82.94%**

### What are the most common genre?
After combining `im.db`, and `tn.movie_budgets.csv.gz`
![Movie Count by Genre](https://github.com/pjsalinas/movies_repo/blob/main/images/movie_count_by_genre.png)

Drama, Comedy, and Action are the dominating factor in the quantity of movies by genre. Does this necessarily mean these are the most profitable genres? In order to determine this we will once again group each genre but this time we are going to take a look at the average net profit for each.


### What is the best time of the year to release a movie?

## Next Steps

## References
Unsplash for the following image: [Unsplash](https://unsplash.com/photos/TFRezw7pQwI)
