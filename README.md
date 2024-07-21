# html-challenge

Background
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.


Note to Grader:
Part 2 had the following lines of starter code for creating the Pandas DataFrame: Create an empty list, mars_temp_date = [], Loop through the scraped data to create a list of rows, rows = table.find_all("tr"), etc. I used the following code which we learned in class to read in HTML tables directly into a DataFrame instead:
#Read in HTML tables into a DataFrame - used code taught in class using Pandas directly
df = pd.read_html("https://static.bc-edx.com/data/web/mars_facts/temperature.html")
mars_df = df[0]
