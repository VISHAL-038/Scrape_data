## Amazon Web Scraping Project

## Overview

This project demonstrates how to perform web scraping using Python to extract product details from Amazon. It uses the BeautifulSoup library for parsing HTML and requests for making HTTP requests. The extracted data includes product titles, prices, ratings, reviews, and availability status, which are then stored in a CSV file.

Libraries Used

BeautifulSoup: For parsing and navigating the HTML structure of the webpage.

Requests: For sending HTTP requests to fetch webpage content.

Pandas: For structuring and exporting data.

NumPy: For handling missing values.

Prerequisites

Install the required Python libraries:

pip install beautifulsoup4 requests pandas numpy

Update the HEADERS dictionary with your browser's user-agent string to mimic a browser request. You can find your user-agent here.

