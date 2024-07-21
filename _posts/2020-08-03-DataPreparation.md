---
title: "Data Collection and Preparation / Database and SQL"
date: 2020-08-03

header:
  image: "/images/Test3.jpg"
  teaser: "/images/nlp/News2.png"
excerpt: "Data Collection, Data Wrangling, SQL, Python"
mathjax: "true"
---

## Mutual Fund Data

### Overview
This project consisted of collecting, cleaning and preparing data from three different sources: a flat file, a website (collected by scraping the website), and an API. The cleaning of the data utilized a pandas DataFrame. The final product included joining all three sources on the same key, storing them in a SQLite database and executing SQL commands to create simple visualizations.

### Tools:

* Pandas
* BeautifulSoup
* SQL
* Sqlite3
* Notebooks

### Part 1 – Flat File Source

The first part of this project was to load a flat file such as a CSV and clean the data.

**Source:** Mutual fund dataset located at: [flat file](https://www.kaggle.com/stefanoleone992/mutual-funds-and-etfs?select=Mutual+Funds.csv){:target="_blank"}

• Demonstrated the following data preparation techniques:

* Find problematic data and fix data types and formats of data values
* Rename columns
* Convert date formats
* Identify and remove duplicate values
* Replace missing values
* Identify and remove erroneous outlier information

### Part 2 – Website Source

The second part of the project was to use BeautifulSoup and scrape a website to retrieve data.

**Source:** Mutual fund financial performance located at: [website](https://charts.ussif.org/mfpc/){:target="_blank"}

• Demonstrated the following data preparation techniques:

* Rename columns to be make consistent for merging with other data frames
* Strip string representation of numbers of dollar signs and letters
* Replace symbols with integers
* Convert data types from strings to floats
* Convert date formats

### Part 3 – API Source

The last data source came from connecting to an API to pull the data.

**Source:** FMP Finance API: [API](https://financialmodelingprep.com/developer/docs/){:target="_blank"}

• Demonstrated the following data preparation techniques:

* Rename columns to be make consistent for merging with other data frames
* Change problematic index
* Convert date datatype to datetime timestamp
* Drop columns
* Replace missing values
* Create new Series with calculated values

### Part 4 – Database and SQL

• Demonstrated the following:

* Creating a SQLite database
* Creating three separate tables
* Performing a left outer join to combine all three tables
* Executing SQL commands to create simple visualizations


### The Complete Project: [here](https://github.com/MaryDonovanMartello/Data-Collection-Preparation-Mutual-Funds){:target="_blank"}.
