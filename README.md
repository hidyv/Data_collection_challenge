# Data_collection_challenge

This project has two parts to create two deliverables:


•	Deliverable 1: Scrape titles and preview text from Mars news articles.

•	Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

The data is collected through web scrapping, extracting information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.

Part 1: Scrape Titles and Preview Text from Mars News


1.	Use automated browsing to visit the Mars news site (https://static.bc-edx.com/data/web/mars_news/index.html) and inspect the page to identify which elements to scrape.

2.	Create a Beautiful Soup object and use it to extract text elements from the website.

3.	Scrape the site to extract titles and preview text of the news articles and store them in Python list of dictionaries.

4.	Export the extracted data as JSON file.

Part 2: Scrape and Analyze Mars Weather Data


1.	Using automated browsing to visit the site (https://static.bc-edx.com/data/web/mars_facts/temperature.html) Inspect the page to identify which elements to scrape.

2.	Create a Beautiful Soup object and use it to scrape the data in the HTML table.

3.	Assemble the scraped data into a Pandas DataFrame.

4.	Examine the data types that are currently associated with each column and change to data types for data analysis.

5.	Analyzing your dataset by using Pandas functions to answer the following questions:

    o	How many months exist on Mars?

    o	How many Martian (and not Earth) days’ worth of data exists in the scraped dataset?

    o	What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:

      	Find the average minimum daily temperature for all the months.

      	Plot the results as a bar chart.

    o	Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:

      	Find the average daily atmospheric pressure of all the months.

      	Plot the results as a bar chart.

    o	How many terrestrial (Earth) days exist in a Martian year? To answer this question:

      	Consider how many days elapse on Earth in the time that Mars circles the Sun once.

      	Visually estimate the result by plotting the daily minimum temperature.

    o	Export the DataFrame to a CSV file.

