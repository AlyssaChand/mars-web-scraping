# mars-web-scraping

These are the sources I used to help me write my codes: pandas.pydata.org, matplotlib.org, google, stackoverflow.com and BCS — watching our cloud recordings, using instructor activity solutions and the class activities as references.

## Part 1: Scrape Titles and Preview Text from Mars News
For this part of the challenge I used automated browsing to visit, inspect, and identify which elements to scrape in the  [Mars news site](https://bootcampspot.instructure.com/courses/5095/assignments/72066?module_item_id=1191885#:~:text=to%20visit%20the-,Mars%20news%20site,Links%20to%20an%20external%20site.,-.%20Inspect%20the%20page). I created a Beautiful Soup object and used it to extract text elements from the website. The titles and preview text of the news articles were scraped and the results were stored in a Python dictionary and then stored in a Python list. For the optional task, I exported the scraped data to a JSON file.

## Part 2: Scrape and Analyze Mars Weather Data
For this part of the challenge I used automated browsing to visit, inspect, and identify which elements to scrape in the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html). I created a Beautiful Soup object and used it to scrape the data in the HTML table. Then I assembled the scraped data into a Pandas DataFrame and converted each column to their appropriate data types. I used Pandas functions to analyze the dataset then exported the DataFrame to a CSV file.
