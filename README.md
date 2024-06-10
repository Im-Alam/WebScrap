# Web Scraping Task

This repository contains a Jupyter Notebook (`.ipynb` file) that demonstrates the implementation of web scraping using the `BeautifulSoup` library to extract useful information from the AmbitionBox website.

## Overview

The primary goal of this project is to scrape data from the AmbitionBox website, focusing on extracting specific company-related information such as:

- Company Name
- Company Rating
- High Rating Values
- Bad Rating Factor
- Review Count
- Salary Comments Count
- Interview Questions Link
- Jobs Count
- Job Link
- Photos Link
- Sector
- Employee Count
- Ownership Type
- Company Age

## Libraries Used

- `BeautifulSoup`: For parsing the HTML content and navigating the parse tree.
- `requests`: For sending HTTP requests to fetch the HTML content from the web pages.
- `re`: For regular expressions to help in extracting specific patterns from strings.

## Features

- **Error Handling**: The implementation includes robust error handling to ensure that missing values are assigned a default value of "NA" instead of causing the program to crash.
- **Data Extraction**: The notebook extracts various pieces of information using the `BeautifulSoup` library, demonstrating how to navigate and query the HTML structure.

## Usage

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Im-Alam/WebScrapingDemo.git
   cd web-scraping-ambitionbox
   
2. **Install dependency**:
    pip install -r requirements.txt


