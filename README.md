# Football Match Scraper (Web Scraping Project)

## Overview

This Python script scrapes football match data from YallaKora.com based on a user-provided date. It collects:

- Championship name
- Teams names
- Match result
- Match time

And saves the data into a CSV file.

## Features

- Web scraping using BeautifulSoup and requests
- Input validation for correct date format (MM/DD/YYYY)
- Error handling to ensure reliable execution
- Data export into CSV file (UTF-8 encoding)
- Deployed as a Streamlit app for a user-friendly interface

## How to Use

1. Install required packages:

    ```bash
    pip install -r requirements.txt
    ```

2. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

3. Open the provided local URL in your web browser to access the user interface.

4. Enter the desired date to scrape football match data and download the results.
