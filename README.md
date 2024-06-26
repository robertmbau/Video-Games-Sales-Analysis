# Video Game Sales Analysis
<a href=/data/video-games-sales.jpg><img src="/data/video-games-sales.jpg" alt="Video Games Sales Analysis"></a>

# Overview
The project analyzes games sales using data from `Kaggle` after it was scrapped from `VGChartz` to uncover insights about the video games industry. Using this data, the aim is ti understand the factors and trends that influence video games sales.
# Table of Contents
- Introduction
- Features
- Requirements
- Data Cleaning and Preparation
- Exploratory Data Analysis
  - Top-Selling Games Analysis
  - Global Sales Distribution
  - Regional Sales Comparison
  - Genre Popularity
  - Yearly Sales Trends
- Conclusion
- Future Work
# Introduction
This project utilizes sales data from `Kaggle` that was scrapped from `VGChartz`. The project aims to explore various aspects of the video game industry to provide insights into factors that drive game sales. Understanding sales patterns and market trends is crucial for developers, publishers and investors.

# Features
- Sales Data Analysis: Analyze sales data across different regions (North America, Europe, Japan, Others, and Global).
- Genre Analysis: Investigate the popularity and sales distribution of different game genres.
- Time-Series Analysis: Analyze how video game sales have evolved over the years.
# Requirements
To run the analysis, you will need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
You can install these libraries using pip.

# Data Cleaning and Preparation
The following were the steps followed:
1. Find missing values
    - In the `Year` column, there was `271` missing values which is `1.63` percent of the whole column. The rows were dropped as it did not constitute a large number.
    - In the `Publisher` column, there was `58` missing values which is `0.35` percent. The rows were dropped.
# Exploratory Data Analysis
1. Top-Selling Games Analysis
  - Analyze the sales patterns of the top 10 best-selling games.
2. Global Sales Distribution
  - Analyze the distribution of global sales among the top-ranked games
3. Regional Sales Comparison
  - Compare the sales in North America, Europe, Japan, and other regions for each game.
4. Genre Popularity
  - Investigate the sales distributions across different genres.
5. Yearly Sales Trends
  - Explore how video game sales have changed over the years for these top games.


Conclusion
1. `Wii Sports` is the highest selling game. This might be attributed to the fact that it is a combination of various games.
2. 

Future Work
1. Scrape more recent data.





