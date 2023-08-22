# Amazon Web Scraping Script - Single Page

This script automates data extraction from a single Amazon search page, collecting product details and exporting them to a CSV file.

## Features

- Scrapes product details from a single Amazon search page.
- Utilizes Selenium and BeautifulSoup libraries.
- Extracts product URL, name, price, rating, and reviews.
- Exports data to a CSV file.

## Usage

1. Clone the repository and navigate to the directory.

2. Install required packages: `pip install selenium beautifulsoup4`.

3. Download appropriate ChromeDriver and set its path in `chromedriver_path`.

4. Run the script: `python amazon_single_page_scraper.py`.

5. Data will be scraped and saved in `Scraped_Data.csv`.

## Notes

- Comply with Amazon's terms of service when scraping.
- Website structure changes may require code updates.

Feel free to customize the script according to your needs and best practices.

**Disclaimer:** Use this script responsibly and ethically. The author is not liable for misuse.

