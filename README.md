# Web Scraper

## Overview

The **Web Scraper** is a Python-based application that allows users to extract important information from a webpage by providing a URL. This tool is designed with a simple and intuitive web interface to enable users to scrape data and download it in various formats such as CSV, PDF, and DOCX.

## Features

- **Data Extraction**: Scrapes key information from user-specified webpages.
- **Multiple Export Formats**: Supports data export in CSV, PDF, and DOCX formats.
- **Built-in Download Options**: Offers easy download functionality directly from the interface.

## Technologies

- **Libraries**:
  - Requests (for making HTTP requests)
  - BeautifulSoup (for parsing HTML and extracting data)
  - ReportLab, pandas, and python-docx (for generating export files)

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.9+
- pip (Python package installer)

### Steps

1. Clone the Repository:

   ```bash
   git clone https://github.com/jashvarthini18/Web_Scraper.git
   cd Web_Scraper
   ```

2. Install Dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Application:

   ```bash
   python app.py
   ```

4. Access the Interface:

   Open your browser and navigate to:

   ```
   http://127.0.0.1:5000
   ```

## Usage

1. **Enter URL**:
   - Enter the webpage URL in the input field and click "Scrape Data."

2. **View Results**:
   - If scraping is successful, the extracted data will be displayed on the page.

3. **Download Data**:
   - Use the provided buttons to download the data in your preferred format (CSV, PDF, or DOCX).
