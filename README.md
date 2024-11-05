# Web Scraping Project

## Project Overview
This project demonstrates web scraping skills using Python to gather data from the web. It focuses on extracting company information, including rankings, industries, revenue, and headquarters location. The project utilizes libraries like `BeautifulSoup` and `requests` to pull data, then organizes and analyzes it with `pandas`.

## Files in This Repository
- `webscraping.ipynb`: The Jupyter notebook file containing the web scraping script and data analysis code.
- `Companies.csv`: A dataset of company information scraped from the web, including fields like Rank, Name, Industry, Revenue, and Headquarters.

## Project Objectives
- **Web Scraping**: Gather company data from an online source.
- **Data Analysis**: Use `pandas` to clean, sort, and analyze the data, making it easier to interpret.
- **Data Visualization**: Present insights about the companies, such as revenue distribution and industry representation.

## Requirements
This project is built with:
- `Python 3.x`
- Libraries:
  - `BeautifulSoup` for parsing HTML content
  - `requests` for making HTTP requests
  - `pandas` for data handling

You can install these libraries using:
```bash
pip install beautifulsoup4 requests pandas

## Sample Data Fields

Here are some fields in `Companies.csv`:

- **Rank**: Ranking of the company by revenue.
- **Name**: Company name.
- **Industry**: Primary industry of the company.
- **Revenue**: Revenue figures in USD millions.
- **Headquarters**: Headquarters location of the company.
