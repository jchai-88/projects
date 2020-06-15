# Data Science Projects Overview

### Exploring eBay Car Sales
#### Project type: Data Cleaning, Data Analysis
**Aim**

In this project, we'll clean and analyse the data of used car listings from eBay Kleinanzeigen which is a classifieds section of the German eBay website.

**Summary**

In summary, these are the things that we have achieved in this project:
- We cleaned the column names to be snakecase and more descriptive.
- We converted columns with numbers from string to numeric types.
- We dropped columns as majority of their data were similar, namely, nr_of_pictures, seller and offer_type.
- We cleaned the price column of unrealistic values. These were values that were too high or 0.
- We analysed the distribution in the columns with date values, namely, the date crawled, last seen and ad created column.
- We removed unrealistic dates from the registration_year column. These were the dates that were outside of the 1910-2016 range.
- We explored the mean price and mean mileage of the Top 6 Car Brands that are listed on the site. These car brands are Volkswagen, BMW, Opel, Mercedes Benz, Audi and Ford. We found that Volkswagen is the most popular car listed as the mean price is affordable. Additionally, the mean mileage of these listed cars are close in value (124k - 132k km).

---

### Hacker News Post Analysis 
#### Project type: Data Analysis

**Aim**

Hacker News is a site started by the startup incubator Y Combinator where users are able to submit posts, particularly in technology and startup circles. These posts are then voted and commented upon which has a similar concept to reddit.

In this project we'll analyse the posts whose titles begin with either Ask HN or Show HN. We'll compare these two types of posts to determine the following:

* Do Ask HN or Show HN receive more comments on average?
* Do posts created at a certain time receive more comments on average?

**Summary**

In conclusion, we found that Ask HN posts received a greater number of comments on average so we decided investigate further into Ask HN posts. This lead us to conclude that the best hour to create a post that'll receive the most number of comments on average is at 3 pm EST. If that is not achievable, the best time of day to create a post is in the afternoon from 12pm est to 6pm EST. Lastly, we also noted that Show HN posts are more popular/liked by users.

---

### Answering Business Questions in SQL
#### Project type: Data Analysis with SQL

**Aim**

In this project, we will be using the Chinook Database which is a SQLite sample database to answer the following business questions.

1. There are 4 new albums by artists that don't have any tracks in the Chinook record store. Which three should we purchase?
2. Are the sales support agents performing better or worse than others?
3. How do the number of customers and sales compare in different countries?
4. Should the Chinook store only purchase individual tracks from an album instead of the whole album?
5. Which artist is used in the most playlist?
6. How many tracks have been purchased vs not purchased?
7. Is the range of tracks in the store reflective of their sales popularity?
8. Do protected vs non-protected media types have an effect on popularity?

**Summary**

SQL can be a powerful tool to manipulate databases to find solutions to a variety of business questions.
