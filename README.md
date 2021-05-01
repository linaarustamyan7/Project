# TripAdvisor-What-Affects-Restaurant-Reviews-
Scraping TripAdvisor to understand what factors affect restaurants reviews

We have scraped the main details about restaurants in Yerevan, such as address, price range, cuisine type, ratings and reviews,etc. For that purpose, I mainly used scrapy, pandas and regex libraries in Python.

After scraping, we calculate the distance of restaurants from the Republic Square using address by Yandex map API, to understand whether being closer to the centre of the city contributes to its popularity (number of reviews).

Finally, linear regression was applied to show what factors affect restaurants reviews and how.
