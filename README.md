# mars-web-scraping
# Part 1

Instructions
Part 1: Scrape Titles and Preview Text from Mars News
Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.

Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.

Create a Beautiful Soup object and use it to extract text elements from the website.

Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:

Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:

Store all the dictionaries in a Python list.

Print the list in your notebook.

Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)

# Part 2

Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.

Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.

Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location
Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

Analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
Export the DataFrame to a CSV file.

# Complete Work Cited

https://stackoverflow.com/questions/63612438/python-cannot-import-selenium-in-jupyter
https://www.crummy.com/software/BeautifulSoup/bs4/doc/
https://www.tutorialspoint.com/how-to-check-the-data-type-in-pandas-dataframe#:~:text=To%20check%20the%20data%20type%20in%20pandas%20DataFrame%20we%20can,values%20of%20the%20series%20object.
https://www.geeksforgeeks.org/beautifulsoup-object-python-beautifulsoup/
https://chatgpt.com/share/8a9e25a4-1abd-45d9-8a3f-cee0f7090b46
https://subscription.packtpub.com/book/web-development/9781783289554/2/ch02lvl1sec13/creating-a-beautifulsoup-object
https://webscraping.ai/faq/beautiful-soup/how-do-i-extract-text-from-html-elements-using-beautiful-soup
https://stackoverflow.com/questions/2010481/how-do-you-get-all-the-rows-from-a-particular-table-using-beautifulsoup
https://www.geeksforgeeks.org/how-to-push-anything-to-github-using-git-bash/

