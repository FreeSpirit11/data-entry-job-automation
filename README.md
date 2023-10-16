# Data Entry Job Automation

This script automates data entry for job listings from Zillow into a Google Form. It leverages Selenium and BeautifulSoup to collect property information, submits data to the Google Form, and stores it in a Google Spreadsheet.

## Description

Automating data entry for repetitive tasks can save time and reduce errors. This Python script demonstrates how to extract property details from Zillow listings and enter them into a Google Form, making it a valuable tool for data entry professionals.

## Features

- Web scraping using BeautifulSoup to extract property information from Zillow.
- Form submission using Selenium to enter data into a Google Form.
- Automation of repetitive data entry tasks.
- Google Spreadsheet integration to store collected data for efficient management.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/FreeSpirit11/data-entry-job-automation.git
   ```

2. Install the required libraries:

   ```bash
   pip install selenium beautifulsoup4
   ```

3. Set up a Google Form and Google Spreadsheet to store the data.

4. Modify the script with your specific Google Form and Zillow URLs.

5. Run the script:

   ```bash
   python main.py
   ```

## Dependencies

- Python 3
- Selenium
- BeautifulSoup

## Usage

1. Run the script, and it will start scraping property data from Zillow listings.
2. The script will fill in the Google Form with the property details.
3. Data will be submitted to the Google Form.
4. You can retrieve and manage the collected data in the associated Google Spreadsheet.

## Acknowledgement

This project is a part of the "100 Days of Code" challenge by Angela Yu.

## Author
- [Mansi Yadav](https://github.com/FreeSpirit11/data-entry-job-automation)
