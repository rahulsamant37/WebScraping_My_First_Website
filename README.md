# Company Data Scraper

This project scrapes company information from the website [AmbitionBox](https://www.ambitionbox.com/list-of-companies) using Python, BeautifulSoup, and Pandas. The data includes company names, ratings, reviews, company type, headquarters, company age, and the number of employees. It can extract data from multiple pages to build a comprehensive dataset for analysis.

## Features

- Scrapes company data from multiple pages.
- Extracts important details such as:
  - Company Name
  - Rating
  - Number of Reviews
  - Company Type
  - Headquarters Location
  - Company Age
  - Number of Employees
- Handles missing data gracefully by assigning `NaN` where data is unavailable.
- Stores the scraped data in a pandas DataFrame for further analysis or export.

## Libraries Used

- `pandas`
- `requests`
- `BeautifulSoup` from `bs4`
- `numpy`

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rahulsamant37/WebScraping_My_First_Website.git
