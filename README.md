# Mars Data Scraping and Analysis

## Overview

This project is a two-part exploration of Mars data, involving web scraping and data analysis. In the first part, we gather the latest Mars news titles and previews, while in the second part, we focus on scraping and analyzing Mars weather data, specifically temperature and atmospheric pressure information.

### Part 1: Mars News Scraping

#### Description

In Part 1, we employ web scraping techniques to retrieve up-to-date Mars news titles and preview text from a designated website.

#### Process

1. **Automated Website Visit**: We use automated web browsing techniques to access the Mars news site.
2. **Data Scraping**: A Beautiful Soup object is created to extract text elements from the website.
3. **Results Storage**: The extracted news article titles and previews are stored in Python data structures.

### Part 2: Mars Weather Data Scraping and Analysis

#### Description

The second part of this project involves scraping and analyzing Mars weather data, focusing on temperature and atmospheric pressure.

#### Process

1. **Automated Website Visit**: We again utilize automated web browsing, this time to access a Mars Temperature Data Site.
2. **Table Data Scraping**: Data from an HTML table is extracted using Beautiful Soup.
3. **Data Organization**: The scraped data is structured into a Pandas DataFrame.
4. **Data Preparation**: Data types are examined and converted as required.
5. **Data Analysis**: We answer key questions using Pandas functions and create data visualizations for better understanding.
6. **Data Storage**: The data is saved to a CSV file.

## Usage

To use this code, follow these steps:

- Ensure you have the necessary libraries installed, including Splinter, BeautifulSoup, Pandas, and Matplotlib.
- Refer to the provided Jupyter Notebooks, namely `part_1_mars_news.ipynb` and `part_2_mars_weather.ipynb`, and follow the instructions for running the code.

## Data Storage

The results of our data gathering and analysis are stored as follows:

- The scraped Mars news data is saved in JSON format, accessible in the 'scraped_data.json' file.
- The Mars weather data, meticulously analyzed and structured, is preserved in a CSV file named 'mars_weather_data.csv'.

## Authors

- Jorge Nardy

## License

This project operates under a specific license, which you can learn more about in the 'LICENSE' file.

---

If you have any inquiries or require further assistance, feel free to reach out.
All information provided by University of Toronto. 
