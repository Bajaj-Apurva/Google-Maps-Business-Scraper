# Google-Maps-Business-Scraper
This script allows you to scrape business details from Google Maps based on a user-defined keyword.
It automates the process of collecting business names, addresses, and websites by leveraging Selenium and web scraping techniques.

## Features
#### Automated Scraping:
The script uses Selenium with Chrome in headless mode to navigate Google Maps and collect business data.
#### Data Extraction:
Extracts business names, addresses, and websites from Google Maps search results.
#### Error Handling:
Includes retry mechanisms to handle exceptions and ensure the script continues to run smoothly.
#### Data Output:
Stores the collected data in a structured format (can be exported to an Excel file using Pandas).

## Setup and Usage
#### Install the required libraries:
pip install selenium beautifulsoup4 requests pandas selenium-stealth chromedriver-autoinstaller

#### Run the script:

python Scrape_GMB_details.py

The script will automatically launch a Chrome browser in headless mode, search for the specified businesses, and extract relevant details.

## Notes
#### Headless Mode: 
The script runs Chrome in headless mode, meaning it operates without opening a visible browser window.
#### Customizable:
You can modify the script to extract additional information or tailor it to specific needs.
