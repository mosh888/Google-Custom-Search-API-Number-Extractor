Google Custom Search API Number Extractor

Overview

The Google Number Extractor is a Python script designed to extract phone numbers and text content from web pages based on company names. 
The script uses the Google Custom Search API to find relevant web pages and then scrapes these pages using BeautifulSoup.

Features:

Reads company names from an Excel file.
Uses the Google Custom Search API to find company web pages.
Scrapes web pages for phone numbers and text content.
Displays unique phone numbers and extracted text content.

Requirements:

Python 3.x
requests library
pandas library
openpyxl library (for Excel file handling)
beautifulsoup4 library (for web scraping)
Google Custom Search API key and Search Engine ID
