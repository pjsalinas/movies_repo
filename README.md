# Microsoft Movies Project
[Pedro J. Salinas](pedrojsalinas@gmail.com)

![Unsplash](https://unsplash.com/photos/TFRezw7pQwI)

### Repo Contents
- [Exploratory Notebooks]()
- Report Notebook
- Project Presentation
- Project Data
- [References](#references)
- Project Source Code
- Project Visuals


### Table of Contents
- [Introduction](#introduction)
- [Project Overview](#overview)
- [Data](#data)
- [Results](#results)
- [Next Steps](#next steps)

## Introduction
This project analyzed the movie industry on behalf of Microsoft Inc., which is considering investing in the movie business. Due to the numerous factors that influence the success of a movie across various platforms, and considering Microsoft's time constraints and pressure, we focused on analyzing a limited number of key parameters to gain insights and generate actionable recommendations for the Microsoft board of directors.

## Overview
Microsoft is exploring the possibility of entering the movie industry using its surplus cash. In 2019, the movie business was valued at $42.2 billion, while the global film industry, including box office and home entertainment revenue, was worth $136 billion in 2018. To assess the viability of such an investment, Microsoft is planning to conduct a thorough analysis of the movie business, focusing on aspects such as profitability and budget. Once the Microsoft board approves the investment, the company will move forward with hiring directors, writers, and actors.

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

![Movie Count by Genre](https://github.com/pjsalinas/movies_repo/blob/main/images/count_movies_by_month.png)

As you can see December is the best month where most movies are released having the last quarter of the year the quarter that most movies are released. Does it mean profitability? 

![Movie Count by Genre](https://github.com/pjsalinas/movies_repo/blob/main/images/profit_by_month.png)

![Movie Count by Genre](https://github.com/pjsalinas/movies_repo/blob/main/images/profit_margin_by_month.png)

May, June and July are the best months to release a movie and obtain a good profit.
Taking about profit margins, January is the best month to release a movie but one more time May, June and July also still good months to release movies. It appears that the beginning of the summer is a good time to release movies.

## Results
* Starting with a production budget of $104078951 will allow Microsoft to obtain a margin profit of 82.94%
* Microsoft should concentrated in the 6 best genres: Adventure, Action, Comedy, Drama, Sci-Fi and Animation. Where Sci-Fi and Animation have less competition.
* The best months to release a profitable movie are May, June, and July.

## Next Steps
- Analysing profit margin for movies with award winning actors, directors and writers.
- The impact in profits a movie might have after the presentation in a premier film festival such Cannes.
 
## References
Unsplash for the following image: [Unsplash](https://unsplash.com/photos/TFRezw7pQwI)
