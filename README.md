# Swiggy-Scrape
### Context

Swiggy is an Indian online food ordering and delivery platform. Founded in July 2014, It is based in Bangalore and operates in 500 Indian cities as of September 2021. Swiggy is the most on-demand food delivery platform that brings food from neighborhood restaurants directly to customers' doors.

### About

Programmed a web scraper using Python packages Beautiful Soup (bs4), Requests, and Pandas to scrape Swiggy public page top restaurants in Delhi data and save the data in csv format.
Efficiently scraped 800 rows of unique and consistent data by Parsing through each restaurants page, to collect information like name, cuisine, rating, number of ratings, and the price for two. The source of data set is Swiggy's official website. Here is the link - https://www.swiggy.com/restaurants/chilis-american-grill-and-bar-outer-circle-connaught-place-delhi-31716


### Project outline

- We'll grab a list of names, and urls of top rated restaurants in Delhi on Swiggy, and put them in 'rest_page.csv'.

- Then we'll grab information like name, cuisine, location, rating, number of ratings, and price for two for each restaurant and save them in 'rest_delhi.csv'.

- The restaurants information will be stored in a csv file with format:

```
name,cuisine,rating,price
Chills,italian, 5, ₹800
```
