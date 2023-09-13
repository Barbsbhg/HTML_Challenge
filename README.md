# **HTML_Challenge**

# **Background**
You’re ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

## **What You're Creating**
This new assignment consists of two technical products. You will submit the following deliverables:

  * Deliverable 1: Scrape titles and preview text from Mars news articles.

  * Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

## **Instructions**
### **Part 1: Scrape Titles and Preview Text from Mars News**
Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.

  1. Use automated browsing to visit the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html). Inspect the page to identify which elements to scrape.
  2. Create a Beautiful Soup object and use it to extract text elements from the website.
  3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
 * Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:/

         {'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
        'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
  
  * Store all the dictionaries in a Python list.

  * Print the list in your notebook.

4. Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)

### **Part 2: Scrape and Analyze Mars Weather Data**
Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.

1. Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

    * <code style="color: red;" >id</code>: the identification number of a single transmission from the Curiosity rover
    * <code>terrestrial_date</code>: the date on Earth
    * <code>sol</code>: the number of elapsed sols (Martian days) since Curiosity landed on Mars
    * <code>ls</code>: the solar longitude
    * <code>month</code>: the Martian month
    * <code>min_temp</code>: the minimum temperature, in Celsius, of a single Martian day (sol)
    * <code>Pressure</code>: The atmospheric pressure at Curiosity's location
  
4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate <code>datetime</code>, <code>int</code>, or 





















     

