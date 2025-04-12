# Jumia Web Scraping Project

## Introduction
This project focuses on web scraping the Jumia Nigeria website to extract product information from the laptops category. The goal is to automate the collection of structured data, such as product names, prices, and ratings, for analysis and reporting. Python was used as the primary programming language, leveraging libraries like `requests`, `BeautifulSoup`, and `pandas` for data extraction, parsing, and transformation.

## Process
1. **Setup**:
   - Installed necessary libraries: `requests`, `BeautifulSoup`, `fake_useragent`, and `pandas`.
   - Configured headers with a random user agent to mimic real browser requests.

2. **Data Extraction**:
   - Sent HTTP requests to the Jumia laptops category page.
   - Parsed the HTML content using `BeautifulSoup` to locate relevant product information.
   - Extracted product names, current prices, old prices, and ratings from the HTML structure.

3. **Data Transformation**:
   - Cleaned and structured the extracted data into lists.
   - Created a `pandas` DataFrame to organize the data into a tabular format.

4. **Output**:
   - Displayed the final dataset containing product details.
   - The data can be exported to a CSV file for further analysis.

## Tech Tools
- **Python**: Core programming language for scripting.
- **Requests**: For sending HTTP requests to the target website.
- **BeautifulSoup**: For parsing and extracting data from HTML content.
- **Fake UserAgent**: For generating random user agents to avoid detection.
- **pandas**: For data manipulation and creating structured datasets.

## Conclusion
The project successfully automated the extraction of product details from Jumia's laptops category. The structured dataset generated can be used for price comparison, market analysis, or other business insights. This project demonstrates the effectiveness of web scraping for data collection and highlights the importance of handling dynamic web elements and anti-scraping measures.

### Tags
- Web Scraping
- Python Automation
- Data Extraction
- BeautifulSoup
- Jumia Nigeria
- E-commerce Analysis
- Data Analysis