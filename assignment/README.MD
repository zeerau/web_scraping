# NAFDAC Web Scraping Project

## Introduction
This project focuses on automating the extraction of product data from the NAFDAC Green Book website. Using Python and Selenium, the script interacts with the website's dynamic elements to scrape product information, such as categories and detailed data from tables, and stores the results in a structured CSV file for further analysis.

## Process
1. **Setup**:
   - Imported necessary libraries, including Selenium, BeautifulSoup, pandas, and others.
   - Configured the Chrome WebDriver for browser automation.

2. **Website Interaction**:
   - Navigated to the NAFDAC Green Book website.
   - Used Selenium to interact with dropdown menus, buttons, and pagination.
   - Dynamically selected product categories (e.g., "Vaccines and Biologics") and adjusted the number of rows displayed per page.

3. **Data Extraction**:
   - Located and extracted data from HTML tables using Selenium.
   - Handled pagination to scrape data across multiple pages.
   - Stored the extracted data in a list of lists for further processing.

4. **Data Transformation**:
   - Converted the scraped data into a pandas DataFrame.
   - Ensured the data was clean and properly structured with appropriate column headers.

5. **Output**:
   - Saved the final dataset to a CSV file (`nafdac_data.csv`) for easy access and analysis.

## Tech Tools
- **Python**: Core programming language for scripting.
- **Selenium**: For browser automation and interaction with dynamic web elements.
- **BeautifulSoup**: For parsing HTML content (if needed).
- **pandas**: For data manipulation and creating structured datasets.
- **Chrome WebDriver**: For automating Chrome browser interactions.

## Conclusion
The project successfully automated the extraction of product data from the NAFDAC Green Book website. The resulting CSV file provides a structured dataset that can be used for further analysis or reporting. This project highlights the effectiveness of Selenium in handling dynamic web pages and extracting valuable information.

### Tags
- NAFDAC Web Scraping
- Python Automation
- Selenium
- Data Extraction
- Dynamic Web Pages
- CSV Export