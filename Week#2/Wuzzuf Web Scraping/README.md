# Wuzzuf Web Scraping Project
## Project Overview
This project involves web scraping job listings from [Wuzzuf](https://wuzzuf.net/) , one of the leading job platforms in Egypt. We collected data for multiple in-demand tech roles to analyze trends and extract useful insights from the job market.

## Targeted Job Titles
- Machine Learning

- Data Analysis

- Data Science

- Business Intelligence

## Extracted Data Fields
For each job listing, the following information was scraped:

- Title: The job title posted on Wuzzuf

- Link: Direct URL to the job post

- Occupation: General role or specialization

- Company: Name of the hiring company

- Specs: Additional job information (e.g., full-time, experience level)

- Location: Job location
## Key Features
✅ Object-Oriented Programming (OOP): The scraper is modular and organized using Python classes for better scalability and readability.

✅ Multi-page Scraping: The scraper automatically navigates through all available pages of search results to collect complete job data.

✅ CSV Export: All scraped data is saved into a structured .csv file for further analysis or use in other tools.


## Tools & Libraries Used
- requests – For sending HTTP requests

- BeautifulSoup – For parsing and navigating HTML content

- pandas – For storing and handling the scraped data

- time – To handle delays and avoid getting blocked (not included in this projects but it's best to add it)

## Future Enhancements
Build visualizations or dashboards using the collected data
