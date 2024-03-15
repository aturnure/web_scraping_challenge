# web_scraping_challenge
This module utilizes BeautifulSoup to scrape various pieces of data from news articles.
In this module, web scraping and data analysis are performed in two parts, each regarding web info on Mars.

# Deliverable 1: Scrape titles and preview text from Mars news articles.
  1. Use automated browsing to visit the Mars news siteLinks to an external site. Inspect the page to identify which elements to scrape.
  2. Create a Beautiful Soup object and use it to extract text elements from the website.
  3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures.
     
# Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
  1. Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site. Inspect the page to identify which elements to scrape.
  2. Create a Beautiful Soup object and use it to scrape the data in the HTML table.
  3. Assemble the scraped data into a Pandas DataFrame.
  4. Analyze your dataset by using Pandas functions to answer the following questions:
         1. How many months exist on Mars?
         2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
         3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
         4. Which months have the lowest and the highest atmospheric pressure on Mars?
         5. About how many terrestrial (Earth) days exist in a Martian year?
  5. Export the DataFrame to a CSV file.

# Resources: 
  Instructions from: https://bootcampspot.instructure.com/courses/4737/assignments/68485?submitted=2
  Data from: https://static.bc-edx.com/data/web/mars_news/index.html and https://mars.nasa.gov/
