# Mini Project 1 – Where do I fly next?

## Abstract
The report presents a systematic approach to Exploratory Data Analysis (EDA) of flight data obtained from Online Travel Agent (OTA) websites such as Expedia, Momondo, and Kayak. Web scraping techniques are employed to collect comprehensive flight information, including prices, airlines, departure times, arrival times, layover cities, layover times, aircraft types, and trip durations. The collected dataset is cleaned and preprocessed for data quality and consistency. Python libraries, including Selenium, BeautifulSoup, Pandas, Seaborn, and Matplotlib, are utilized for web scraping, data manipulation, and visualization. The report also discusses real-time interactions with end users using Ipywidgets.

## 1. Introduction
Flight booking websites provide a convenient way for travelers to compare prices and book flights. The report addresses the challenge of sifting through overwhelming options by employing web scraping techniques to collect relevant flight data. The focus is on acquiring consistent and instant data from OTA websites for in-depth analysis.

## 2. Data Collection
### 2.1 Data Understanding
The report defines key data elements to be extracted, such as price, number of stops, airline, departure time, arriving time, and more. The data structure on OTA websites is analyzed to facilitate scraping.

### 2.2 Data Scraping
Various tools, including Scrapy, BeautifulSoup, and Selenium, are compared, and Selenium is chosen for scraping dynamic content. The challenges of anti-bot mechanisms are addressed using specialized packages like "selenium_stealth."

## 3. Data Analysis (EDA)
### 3.1 Overview
The compiled flight information is subjected to Exploratory Data Analysis (EDA) to understand data types, missing entries, and summary statistics. Data preprocessing tasks include type conversion and format adjustments.

### 3.2 Data Visualization
#### 3.2.1 Price
The distribution of prices is visualized, including box plots to identify outliers.

#### 3.2.2 Number of Stops
The distribution of the number of stops is explored, and a correlation with price is established.

#### 3.2.3 Layover Cities
The prevalence of layover cities is visualized, highlighting frequent layover locations.

#### 3.2.4 Layover Time
The distribution of layover times is presented, including box plots.

#### 3.2.5 Total Trip Duration
The distribution of total trip duration is analyzed, providing insights into typical travel times.

## 4. User Interaction
Ipywidgets are employed for user interaction, allowing users to modify data, adjust parameters, and observe instant updates in visualizations or calculations.

### 4.1 Ipywidgets Package
The utilization of widgets, such as sliders and dropdown menus, is discussed for effective user interaction.

### 4.2 User Interaction Design and Implementation
The process of generating widgets, executing them, establishing a DataFrame Cast, and obtaining filtered DataFrame results is explained. Formatted flight information is displayed based on user input.

## 5. Conclusion
The project provides a comprehensive experience of the data lifecycle, emphasizing the importance of data acquisition, cleaning, and exploratory data analysis. Key findings include insights into price distribution, layover cities, and the impact of departure times on ticket prices.

## References
- S. Ravinder. Web scrapping dynamic content using API and BeautifulSoup, 2021. [Source](https://www.numpyninja.com/post/web-scrapping-dynamic-content-using-api-and-beautiful-soup)