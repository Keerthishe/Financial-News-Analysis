This project performs data analysis and visualization on a dataset of Indian financial news articles. It aims to explore trends, distributions, and insights over time and across different days of the week.

Project Overview
Load and preprocess news dataset

Handle missing values and clean data

Filter news from 2010 to 2020 for analysis

Visualize monthly article counts to observe trends over time

Visualize article distribution by day of the week

Use libraries like Pandas, Matplotlib, Seaborn for data manipulation and plotting

Dataset
The dataset is expected as a CSV file named IndianFinancialNews.csv

It contains news article metadata including columns like Date, Title, DayOfWeek, Year, and Description

Features
Data cleaning: Handling missing values, removing unwanted columns

Data type conversion for proper time series handling

Time series resampling by month to count the number of articles

Line plot showing monthly article publication trends (2010-2020)

Bar plot showing distribution of articles published by day of the week

Technologies and Libraries
Python 3.x

Pandas (data manipulation)

Matplotlib and Seaborn (visualizations)

NLTK (for text processing if extended)

WordCloud and collections (potential for text analytics)
