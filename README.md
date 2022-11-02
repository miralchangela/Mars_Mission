# Mars_Mission

## Overview of the project:
The mission to mars project for to take on the full web-scraping and data analysis.we can identify HTML elements on a page, identify their id and class attributes. Using this knowledge, we can extract information via automated browsing with Splinter and HTML parsing with Beautiful Soup.Various types of information scraped such as HTML tables and recurring element from multiple news articles on a webpage.In this project , we scraped, organized, analyzed, and visualized the data.

## Scrape Titles and Preview Text from Mars News:

* Scraped the [Mars News](https://redplanetscience.com/) website by using Splinter and Beautiful Soup.Specifically, scraped the title and preview text, or summary text, of each article on the landing page.
* Store the scraping results in Python data structures.Store each title and preview pair in a Python dictionary.Store all the dictionaries in a Python list. The following image is list of title and preview pair dictionary.

![title_preview](https://github.com/miralchangela/Mars_Mission/blob/main/Images/title_preview.png)

* After that,store the scraped data in a file or database.so, we export the scraped data to either a JSON file and a MongoDB database.'

## Scrape and Analyze Mars Weather Data:

* From the [ Mars Temperature Data](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) website scraped the data in the HTML table.

* There are two ways to find HTML Table from website.The first way,is to use Pandas's * read_html * method. The second way, is to manually scrape the data by using Splinter and Beautiful Soup.

* Now , we could asssemble the scraped data into a Pandas DataFrame.The columns should have the same headings as the table on the website.

![datatype](https://github.com/miralchangela/Mars_Mission/blob/main/Images/datatype.png)

* Examine the data types of all the DataFrame columns. If necessary, Convert the data to the appropriate datetime, int, or float data types. its image is shown below.

![changed_datatype](https://github.com/miralchangela/Mars_Mission/blob/main/Images/changed_datatype.png)

* Furthermore, we can plot the graph for finding answers to questions.

* The following image gives the information about What are the coldest and the warmest months on Mars. From the graph, we can clearly see that month 3 is the coldest month with -90.0 degree minimum tempreture when month 1 is the warmest month with -62.0 degree minimum temprature.

![temp_of_all_months](https://github.com/miralchangela/Mars_Mission/blob/main/Images/temp_of_all_months.png)

* The following image gives the information about Which months have the lowest and the highest atmospheric pressure on Mars. Graph shows that month 5 has  lowest atmospheric pressure with 727.0 when month 9 has highest atmospheric pressure with 925.0.

![prsr_of_all_months](https://github.com/miralchangela/Mars_Mission/blob/main/Images/pressure_of_all_months.png)

* The following plot visually estimates the result by plotting the daily minimum temperature.
*
![Daily_minimum_tempreture](https://github.com/miralchangela/Mars_Mission/blob/main/Images/Daily_minimum_tempreture.png)
