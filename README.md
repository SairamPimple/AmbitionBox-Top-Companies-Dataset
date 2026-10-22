# AmbitionBox-Top-Companies-Dataset

## Project Overview
This project focuses on web scraping company information from AmbitionBox using Python. The collected data was structured, cleaned, and stored in a CSV file for further analysis, visualization, and employment trend insights.

The objective of this project is to demonstrate practical skills in web scraping, data extraction, data cleaning, and data handling using Python.

## Dataset Information
The dataset contains information about top companies listed on AmbitionBox, including:
- Company Name
- Overall Rating
- Number of Reviews
- Salary Records
- Interview Records
- Job Openings
- Benefits Information
- Highly Rated Areas
- Critically Rated Areas
- Industry Domain
- Primary Location
- Office Count

## Technologies Used
- Python
- Requests
- BeautifulSoup
- Pandas

## Project Workflow
1. **Data Collection**
   - Sent HTTP requests to target AmbitionBox directory pages.
   - Retrieved raw HTML content from multiple listing pages.
2. **Data Extraction**
   - Parsed HTML using BeautifulSoup.
   - Extracted company-related attributes, metrics, and metadata.
3. **Data Cleaning & Structuring**
   - Handled missing values across ratings, feedback, and domain attributes.
   - Standardized text and preserved metric formats.
4. **Data Storage**
   - Converted extracted information into a Pandas DataFrame.
   - Exported the final structured dataset to CSV format (`ambitionbox_top_companies.csv`).
  


## Dataset Columns

| Column Name | Description |
| :--- | :--- |
| **`name`** | Company name |
| **`rating`** | Overall company rating out of 5.0 |
| **`reviews`** | Total review count |
| **`salaries`** | Total salary records |
| **`interviews`** | Total interview experiences |
| **`jobs`** | Active job openings |
| **`benefits`** | Total benefit reviews |
| **`Highlyratedfor`** | Areas where the company is highly rated |
| **`Criticallyratedfor`** | Areas where the company receives critical ratings |
| **`domain`** | Industry domain or sector |
| **`location`** | Primary location or head office hub |
| **`office_count`** | Number of offices across India |



## Files in this Repository
- **`web_scraper_script.py`**: Python script containing the automated web scraping and data extraction logic.
- **`ambitionbox_top_companies.csv`**: Final structured dataset generated from the web scraping process.

## Skills Demonstrated
- Web Scraping & Automation
- Data Collection
- Data Cleaning & Preprocessing
- Data Transformation
- Data Analysis Preparation
- Pandas DataFrame Operations
- Handling Missing Data
- Working with Real-World Web Datasets

## Future Improvements
- Perform Exploratory Data Analysis (EDA) on salaries and ratings across different industry domains.
- Create Data Visualizations to map company locations and office footprints.
- Build interactive company rating dashboards.
- Compare industry segments and workplace satisfaction factors.

## Note
This project and dataset were created strictly for educational and analytical purposes using publicly accessible company information from AmbitionBox.

## Author
Sairam Pimple
Data Analytics & Data Science Enthusiast
