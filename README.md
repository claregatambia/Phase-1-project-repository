# MICROSOFT’S NEW MOVIE STUDIOS PROJECT: Analysis of Information from Box Office Metrics
## Overview
Microsoft was founded in 1975 by Bill Gates and Paul Allen in Redmond, Washington, USA. It has since
become one of the world's largest and most influential technology companies. It has undergone several
strategic shifts over the years, evolving from a software company to a diversified technology and cloud
computing giant.
Microsoft's foray into the entertainment industry represents a strategic expansion beyond its traditional
technology offerings. It is a new venture under the Microsoft Corporation umbrella, aimed at entering the
highly competitive and dynamic film industry. A subsidiary of Microsoft Corporation, Microsoft Movie
Studios are prepared to enter the film business with a strategic strategy that will make use of its technology
resources and skills. This business case describes the justification, goals, and important factors for the
founding and expansion of Microsoft Movie Studios in the fiercely competitive filmmaking industry
You've made it all the way through the first phase of this course - take a minute to celebrate your awesomeness!

## Business Understanding
Microsoft's interest in creating a movie studio reflects its desire to diversify revenue streams and
leverage its brand recognition to compete in the entertainment sector. Understanding Microsoft's
broader business context will be essential for tailoring your recommendations to align with the
company's overall objectives and ensuring the success of the new movie studio within the larger
Microsoft ecosystem.
Creating a successful movie studio requires a deep understanding of current industry trends and
audience preferences. To help Microsoft's new movie studio make informed decisions about the types
of films to produce, here are some insights into what's performing well at the box office. The studio aims
to create compelling and entertaining content that resonates with audiences worldwide
Microsoft's new movie studio lacks domain expertise in filmmaking and needs guidance on which film
genres to focus on to maximize box office success. Leveraging historical box office data and exploring
genre trends, this investigation will guide the choice of films they should produce. Box office revenues,
ROI and ratings data will serve as indicators of financial viability and audience reception across different
film genres.

## OBJECTIVES
Main Objective of the Study: The main objective of this study is to analyze historical film data and
identify features top movies share. Outcomes will determine the types of films to create, maximizing the
chances of success. The specific objectives include:
1. To determine the genres with the highest potential for success in the market in terms of revenue
and audience reception.
2. To investigate additional factors such as budget, studio, and target audience demographics, to
determine their impact on a film's success.
3. Based on the analysis, derive actionable insights and recommendations that align the studio's
content strategy with audience preferences and market trends to increase the probability of
producing commercially successful films.

## DATA UNDERSTANDING
The dataset comprises historical data from Imdb and box office with information on genre, title, budget,
gross profits and other features we can analyze to find out more about performance of movies. According
to imdb pro, a film has to make around double its cost to break even. Distributions receive money known
as rentals that is nearly 50% of gross earning. Some movies spend more on advertising but this is covered
by ancillary streaming and tv revenue whose data we do not have access to. A film of 100m budget needs
to make at least 255m to break even. https://pro.imdb.com/content/article/entertainment-industryresources/featured-articles/how-is-the-success-of-films-and-tv-shows-measured/GLFTC8ZLBBUSNTM3

## DATA ANALYSIS
The data was extracted from three datasets that were in a comma separated values format(csv). The files
were then inspected for inconsistencies such as missing values, duplicates or anomalies. Explanatory data
analysis was then adopted in order to gain further insights of the datasets. The data visuals extracted from
analysis of the data rea shown below:
On average, movies in the tmdb_movies.csv dataset have received a rating of 6.0, and approximately 50%
of the movies have a rating below 6.0, as indicated by the median.
The standard deviation of 1.853 measures dispersion. A larger value indicates greater spread, while
smaller values indicate that data points are clustered around the mean.
The ratings range from 0 to 10. With a standard deviation of 1.853, the ratings exhibit some variability
but are not extremely spread out. According to the boxplot, ratings below 2 can be considered as outliers.
Since our interest lies in movies that perform well, we will drop rows with low ratings.
It is essential to interpret ratings and vote counts within the appropriate context. A low vote count, despite
yielding a higher average rating, may not accurately reflect the opinions of the general public. Instead, it
suggests that the movie in question has found success within a smaller, dedicated group of viewers who
appreciate its distinct qualities.
Total gross and Profitability: There is a strong positive correlation of 0.941 between the total gross and
profitability of movies. This indicates that as the total gross increases, the profitability tends to increase as
well. This suggests that movies with higher box office earnings are more likely to be profitable.
Production Budget and Profitability: The correlation between production budget and profitability is
relatively weak, with a value of 0.172. There is limited association between the production budget of a
movie and its profitability. A higher production budget does not necessarily guarantee higher profitability.
Other factors, such as marketing, distribution, and audience reception, may play significant roles in
determining a movie's profitability.
Rating and Profitability: The correlation between the movie rating and profitability is negative, with a
value of -0.235. This suggests that there is a weak inverse relationship between the rating of a movie and
its profitability.
Based on our analysis and inference, the most popular genres were:
*  Genre ID 12: Adventure
*  Genre ID 28: Action
*  Genre ID 10751: Family
*  Genre ID 14: Fantasy
*  Genre ID 10402: Music
*  
## RECOMMENDATIONS
1. Prioritize producing movies in these genres which have shown a higher prevalence and audience
interest;
* Adventure
* Action
* Family
* Fantasy
* Music
2. Prioritize strategies that aim to maximize both profitability and total gross given the positive
relationship between profitability and total gross observed in the dataset of high-performing
movies.
3. Carefully manage and optimize the production budget. A higher production budget does not
guarantee higher profitability.
4. Positive ratings and critical acclaim can contribute to the reputation of the studio and help in
building a loyal audience base.
5. The studio should aim to increase its movie production output. More movies can lead to higher
overall gross sales, provided they align with popular genres and maintain a focus on profitability

