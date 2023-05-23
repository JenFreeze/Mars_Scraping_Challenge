# Mars_Scraping_Challenge

## Overview
In this challenge, we used Splinter, HTML, and Beautiful Soup to scrape various pieces of information from websites containing Mars data. 

## Part 1: Scrape Titles and Preview Text from Mars News
- For Part 1, we used automated browsing in Google Chrome to open the Mars News website and pull the title and preview of each article listed.
- We then created dictionaries in Python to store each article's title and preview.
- All of the dictionaries were then saved into a Python list. 

## Part 2: Scrape and Analyze Mars Weather Data
- For Part 2, we used automated browsing and Beautiful Soup to pull Mars Weather data from a table on the Mars Temperature Data site.
- Once we had the table data, we saved this into a Pandas Dataframe so that it was easier to analyze and manipulate. Each row of the Dataframe included:
    - ID
    - Terrestrial Date (date on Earth)
    - Number of elapsed Martian days (sol)
    - Solar longitude
    - Martian month
    - Minimum temperature in Celsius
    - Atmospheric pressure
- Based on our analysis, we came to the following conclusions:
    - There are 12 months on Mars.
    - We had 1867 Martian days worth of data in the dataset.
    - The third month tends to be the coldest on Mars, and the eighth month tends to be the warmest.
    - The sixth month has the lowest atmospheric pressure, and the ninth month has the highest.
    - A year on Mars appears to be approximately 675 Earth days.