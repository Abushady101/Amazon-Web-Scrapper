# Amazon Web Scraper

## Overview

This project is an Amazon Web Scraper written in Python, designed to extract data (such as product titles, prices, and ratings) from Amazon product listings using Python notebooks.

---

## Features

- **Automated scraping**: Extracts key product information from Amazon.
- **Customizable**: Modify the target URL, number of pages, and extracted fields.
- **Data Export**: Results can be exported as CSV or JSON for further analysis.

---

## Installation

To run this web scraper, follow the steps below:

### Prerequisites

- Python 3.x
- Jupyter Notebook or another IDE that supports Python notebooks
- Required packages: Install the following dependencies using `pip`:

bash

Copy code

`pip install requests pip install beautifulsoup4 pip install pandas`

### Optional Libraries

- **Selenium**: If you wish to extend this scraper for dynamic content.
- **Scrapy**: For advanced scraping purposes.

---

## Usage

1. **Set Up Your Environment**: Make sure the required libraries are installed.
2. **Load the Notebook**: Open the provided Jupyter Notebook.
3. **Run the Notebook Cells**: Start from the top cell, modify the product search URL and other parameters to suit your needs, and then run the notebook to scrape the data.
4. **Extracted Data**: The notebook will display the extracted product data and allow exporting it to a file.


## Notes

- **Anti-scraping measures**: Amazon has strict anti-scraping policies. To avoid being blocked, implement measures such as:
    - Using rotating IP addresses
    - Adding random delays between requests
    - Respecting the site's robots.txt and terms of service
- **Legal Disclaimer**: This project is intended for educational purposes only. Ensure you comply with Amazon's policies and guidelines before scraping.

---

## Future Enhancements

- **Handling Pagination**: Scrape multiple pages automatically.
- **Adding More Features**: Extract additional data like customer reviews, product images, etc.
- **Selenium Support**: Handle dynamic content with Selenium.

---

## Contributing

Feel free to submit a pull request or raise an issue to suggest improvements!

---

## Acknowledgments

- BeautifulSoup for HTML parsing.
- Pandas for data handling.