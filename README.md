# Mars Data Scraping and Analysis

## Overview
This project involves scraping data from the Mars News website and the Mars Temperature Data site. The assignment is divided into two main parts:

1. **Scrape Titles and Preview Text from Mars News Articles.**
2. **Scrape and Analyze Mars Weather Data.**

## Deliverables

### Deliverable 1: Scrape Titles and Preview Text from Mars News
- Scrape the titles and preview text from Mars news articles.
- Store the scraped data in a Python dictionary with keys `title` and `preview`.
- Print the list of dictionaries.
- Optionally, export the data to a JSON file.

### Deliverable 2: Scrape and Analyze Mars Weather Data
- Scrape and assemble Mars weather data into a Pandas DataFrame.
- Analyze the dataset to answer specific questions about Mars' weather patterns.
- Export the DataFrame to a CSV file.

## Files
- `part_1_mars_news.ipynb`: Jupyter Notebook for Part 1.
- `part_2_mars_weather.ipynb`: Jupyter Notebook for Part 2.
- `mars_temperature_data.csv`: CSV file containing the scraped Mars weather data.

## Analysis

### Part 1: Scrape Titles and Preview Text from Mars News

1. **Open `part_1_mars_news.ipynb`**:
    - Use automated browsing to visit the Mars News Site.
    - Inspect the page to identify elements to scrape.

2. **Scrape Data**:
    - Create a BeautifulSoup object and use it to extract text elements.
    - Extract titles and preview texts.
    - Store each title and preview text pair in a dictionary with keys `title` and `preview`.
    - Store all dictionaries in a list.
    - Print the list of dictionaries.
    - Optionally, export the data to a JSON file.

### Part 2: Scrape and Analyze Mars Weather Data

1. **Open `part_2_mars_weather.ipynb`**:
    - Use automated browsing to visit the Mars Temperature Data Site.
    - Inspect the page to identify elements to scrape.

2. **Scrape Data**:
    - Create a BeautifulSoup object and use it to scrape the data in the HTML table.
    - Assemble the scraped data into a Pandas DataFrame with appropriate column headings.

3. **Analyze Data**:
    - Use Pandas functions to answer specific questions about the dataset, such as:
        - How many months exist on Mars?
        - How many Martian days worth of data exist in the dataset?
        - What are the coldest and the warmest months on Mars?
        - Which months have the lowest and the highest atmospheric pressure on Mars?
        - About how many terrestrial days exist in a Martian year?
    - Plot the results as bar charts for visual analysis.

4. **Export Data**:
    - Export the DataFrame to a CSV file.

## Conclusion
This project demonstrates how to scrape data from web pages and perform data analysis using Python libraries such as BeautifulSoup and Pandas. The extracted data provides valuable insights into Mars' weather patterns and news.
