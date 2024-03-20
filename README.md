# Web Scraping Daraz Products

Welcome to the Web Scraping Daraz Products project! This Python script scrapes product information from Daraz using Selenium and BeautifulSoup.

## Description

The script navigates to the Daraz website, searches for watches, scrapes product details such as title, price, ratings, delivery information, and more, and writes the data to a CSV file.

## Requirements

- Python 3.x
- Chrome browser
- Selenium
- BeautifulSoup
- ChromeDriver

## Installation

### Install Dependencies

# Web Scraping Daraz Products

Welcome to the Web Scraping Daraz Products project! This Python script scrapes product information from Daraz using Selenium and BeautifulSoup.

## Description

The script navigates to the Daraz website, searches for watches, scrapes product details such as title, price, ratings, delivery information, and more, and writes the data to a CSV file.

## Requirements

- Python 3.x
- Chrome browser
- Selenium
- BeautifulSoup
- ChromeDriver

## Installation

### Install Dependencies

pip install selenium webdriver-manager beautifulsoup4


### Download ChromeDriver

Ensure you have ChromeDriver installed.

Usage
Run the `scrape_daraz_products.py` script.
Wait for the script to scrape the data.
Check the generated `products.csv` file for the scraped information.

Data Scraped
- Title: Name of the product.
- Current Price: The current selling price of the product.
- Original Price: The original price of the product before any discounts.
- Sold: Number of units sold.
- Review Amount: Number of reviews for the product.
- Ratings: Average ratings of the product.
- Delivery: Delivery information.
- Vouchers: Available vouchers for the product.
- Web Link: Direct link to the product page.

Acknowledgments
Special thanks to Daraz for providing the platform and to the developers of Selenium and BeautifulSoup for their invaluable tools.
