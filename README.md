# Data Science Projects Overview

**Exploring eBay Car Sales**

In this project, we'll clean and analyse the data of used car listings from eBay Kleinanzeigen which is a classifieds section of the German eBay website.

*Summary*

In summary, these are the things that we have achieved in this project:
- We cleaned the column names to be snakecase and more descriptive.
- We converted columns with numbers from string to numeric types.
- We dropped columns as majority of their data were similar, namely, nr_of_pictures, seller and offer_type.
- We clean the price column of unrealistic values. These were values that were too high or 0.
- We analysed the distribution in the columns with date values, namely, the date crawled, last seen and ad created column.
- We removed unrealistic dates from the registration_year column. These were the dates that were outside of the 1910-2016 range.
- We explored the mean price and mean mileage of the Top 6 Car Brands that are listed on the site. These car brands are Volkswagen, BMW, Opel, Mercedes Benz, Audi and Ford. We found that Volkswagen is the most popular car listed as the mean price is affordable. Additionally, the mean mileage of these listed cars are close in value (124k - 132k km).
