# Git Scraper

I modified the GitScraper to get all of the titles of the Opinion articles on the first page of the Opinions section of the DP. I did this by modifying the scrape_data_point function to find all the h3 tags with the standard-link class, and then I extracted the text data from the a tag which had the titles. I added all of these to an array and then returned this array of article names.
