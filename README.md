# Web_Scraping_python
This Python script scrapes customer reviews for a product iQOO Z7 Pro 5G (Graphite Matte, 8GB RAM, 128GB Storage) | 3D Curved AMOLED Display | 4nm MediaTek Dimesity 7200 5G Processor | 64MP Aura Light OIS Camera | Segment's Slimmest & Lightest Smartphone on Amazon using BeautifulSoup. It retrieves the page content, parses it, and extracts  customer reviews  text.
The project aims to scrape and analyze customer reviews for a specific product listed on Amazon India. It utilizes Python libraries such as BeautifulSoup and requests for web scraping, along with pandas for data manipulation.

Project Details:

Importing Necessary Libraries: The script starts by importing required libraries including sys, time, BeautifulSoup from bs4, requests, and pandas for web scraping and data handling tasks.
1.sys: A Python built-in module for accessing system-specific parameters and functions, commonly used for error handling and command-line interaction.

2.time: Python module for time-related functions, including sleep() for introducing delays in execution, often used in web scraping to control request rates.

3.BeautifulSoup (bs4): A Python library for parsing HTML and XML documents, facilitating easy extraction of data from web pages.

4.requests: A Python library for making HTTP requests, used for retrieving web pages and interacting with web servers.

5.pandas: A powerful Python library for data manipulation and analysis, particularly with tabular data structures like DataFrames, essential for organizing and analyzing scraped data.

Error Handling: An exception handling block is implemented to catch any errors that may occur during the HTTP request. If an error is encountered, it prints the error type and line number for debugging purposes.

HTTP Request: The script sends an HTTP GET request to the Amazon India product page specified by the URL https://www.amazon.in/iQOO-Graphite-MediaTek-Processor-Smartphone/product-reviews/B07WGPKC7H/.

Page Parsing: Once the page is successfully retrieved, the HTML content is parsed using BeautifulSoup, creating a parse tree of the HTML DOM.

Extracting Review Links: Using BeautifulSoup, the script finds all HTML elements (span) with the class a-size-base, which typically contains the review texts.

Printing Review Texts: It iterates through the extracted review elements and prints out the text of each review.

 
