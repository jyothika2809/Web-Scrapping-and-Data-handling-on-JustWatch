# Web-Scrapping-and-Data-handling-on-JustWatch
🎬 JustWatch Web Scraping and Data Handling Project

Welcome to the JustWatch Web Scraping project repository! This project explains of data scrapping from JustWatch, a popular streaming guide that helps users find where to watch movies and TV shows across various platforms.

🚀 Project Overview
This project focuses on scraping movie and TV show data from JustWatch to build a dataset for filtering and analysis. The data collected includes information such as:

Url's of movies and TV shows,
Movie/TV show titles,
Genres,
Release year,
Streaming service details,
Price (rent, buy, or subscription),
Ratings (IMDb,age),
Cast and crew,
Production country details,
Runtime and duration,
Motivation,
This project aims to automate the extraction of valuable information about movies and TV shows for data filtering, analysis and comparison of streaming services. The resulting dataset can be used for building dashboards and performing trend analysis.

🔧 Features:-

Automated(iterating) scraping: Extracts information like titles, genres, streaming platforms, and pricing from JustWatch
Customized filters: Allows scraping data for specific countries, genres, or streaming platforms.
Data export: Exports the scraped data into CSV format for further analysis.

🛠️ Technology Stack

Programming Language: Python
Libraries:
BeautifulSoup: For parsing HTML and extracting data
requests: To make HTTP requests and fetch webpage content
pandas: For cleaning and storing scraped data in a tabular format
re: Regular expressions to extract specific patterns from the website

Steps involved in this project:

1.Installed the necessary libraries(requests, pandas, Beautiful Soup).

2.Running the scrapper code.

3. Data filtering and analysis.

4.Exporting the extracted data into a csv file.

🔄 How It Works

Requesting the JustWatch page: The scraper makes HTTP requests to JustWatch for movie or TV show lists based on user-defined filters.
Parsing HTML content: Using BeautifulSoup, the script extracts relevant information such as titles, genres, ratings and streaming options.
Data storage: The extracted data is cleaned and saved as a CSV file using Pandas for easy analysis.

📊 Data Analysis

After scraping, you can analyze the data to:
Compare prices for streaming services.
Identify which platforms offer specific movies/TV shows.
Analyze trends in streaming availability by genre or country.
Build recommendation systems based on viewing trends.

🤝 Acknowledgments

JustWatch for their platform and content.
Python open-source libraries: BeautifulSoup, requests, and pandas.
