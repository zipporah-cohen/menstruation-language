# menstruation-language
Data science project investigating the language is used in Google Search results pertaining to menstruation.

## Component Files
- **Selenium Data Collection.ipynb:** This notebook uses Selenium to perform Google searches for a set list of queries and saves each resulting HTML locally.
- **Google Scrape Top Results.ipynb:** This notebook contains and calls a function that can scrape the organic search results from locally saved HTML files.
- **Keyword Searching and Data Analysis.ipynb:** This notebook finalizes data collection by getting keyowrd counts from existing HTMLs. It then performs all necessary data analysis for the project. Data analysis is broken up into multiple categories within the notebook: data exploration with exploratory visuals, kNN classification, k-means clustering, and further visuals and statistics.
- **driver:** Folder containing the Chrome Webdriver used with Selenium in data collection.
