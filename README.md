# Mars News and Weather Data Analysis

## Overview

This challenge involves web-scraping and analyzing data from the Mars News website and the Mars Temperature Data site using automated browsing with Splinter and HTML parsing with Beautiful Soup. The challenge is divided into two parts: scraping Mars news articles and scraping and analyzing Mars weather data.

## Challenge Structure

### Instructions

#### Part 1: Scrape Titles and Preview Text from Mars News

1. **Open Jupyter Notebook**:
   - Open the Jupyter Notebook in the starter code folder named `part_1_mars_news.ipynb`.

2. **Automated Browsing**:
   - Use automated browsing to visit the [Mars news site](https://redplanetscience.com).
   - Inspect the page to identify which elements to scrape.

3. **Create Beautiful Soup Object**:
   - Create a Beautiful Soup object and use it to extract text elements from the website.

4. **Extract Titles and Preview Text**:
   - Extract the titles and preview text of the news articles.
   - Store the scraping results in Python data structures:
     - Store each title-and-preview pair in a dictionary with keys `title` and `preview`.
     - Store all dictionaries in a list.
   - Print the list in your notebook.
   - Optionally, export the scraped data to a JSON file for easier sharing.

#### Part 2: Scrape and Analyze Mars Weather Data

1. **Open Jupyter Notebook**:
   - Open the Jupyter Notebook in the starter code folder named `part_2_mars_weather.ipynb`.

2. **Automated Browsing**:
   - Use automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html).
   - Inspect the page to identify which elements to scrape.

3. **Create Beautiful Soup Object**:
   - Create a Beautiful Soup object and use it to scrape the data in the HTML table.

4. **Assemble Data into DataFrame**:
   - Assemble the scraped data into a Pandas DataFrame with columns: `id`, `terrestrial_date`, `sol`, `ls`, `month`, `min_temp`, and `pressure`.
   - Examine and convert data types as necessary.

5. **Analyze Dataset**:
   - Answer the following questions using Pandas functions:
     1. How many months exist on Mars?
     2. How many Martian days of data exist in the dataset?
     3. Coldest and warmest months on Mars (average minimum daily temperature).
     4. Months with the lowest and highest atmospheric pressure.
     5. Estimate the number of terrestrial days in a Martian year.

6. **Export DataFrame to CSV**:
   - Export the DataFrame to a CSV file.


---


