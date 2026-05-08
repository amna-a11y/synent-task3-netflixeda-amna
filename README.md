Task 3 – Exploratory Data Analysis (EDA) – Netflix Dataset
Problem Statement
The objective of this task is to perform Exploratory Data Analysis (EDA) on the Netflix dataset to identify trends, patterns, and meaningful insights. The analysis helps in understanding content distribution, growth trends, and relationships between different features using visualizations.

Dataset Details


Dataset Name: Netflix Dataset


Format: CSV File


Main Focus Columns


type


date_added


country


rating


release_year


Features


Type (Movie / TV Show)


Title


Country


Date Added


Release Year


Rating


Duration



Approach
1. Data Upload and Loading


Dataset uploaded using files.upload() in Google Colab


Loaded using pandas.read_csv()


2. Data Cleaning


Converted date_added column into datetime format


Extracted year_added for yearly trend analysis


Handled missing or inconsistent date values


3. Exploratory Data Analysis (EDA)
Content Type Distribution


Pie chart showing percentage of Movies vs TV Shows


Content Growth Over Time


Line chart representing yearly content additions


Top 10 Countries


Horizontal bar chart showing leading content-producing countries


Ratings Distribution


Bar chart showing the most common content ratings


Release Year Distribution


Histogram displaying distribution of content release years


Movies vs TV Shows Trend


Comparative line chart showing growth over time



Tools and Libraries Used


Python


Pandas


Matplotlib


Google Colab



Code Overview
Main Steps


Upload dataset


Load data into Pandas DataFrame


Clean and preprocess date columns


Generate multiple visualizations:


Pie chart


Line chart


Bar chart


Histogram





Results and Insights


Movies are more common than TV Shows on Netflix


Netflix content additions increased rapidly in recent years


Certain countries dominate content production


TV-MA and TV-14 are among the most common ratings


Most Netflix content was released after 2000


Both Movies and TV Shows show strong growth trends over time



Output Visualizations


Content Distribution Pie Chart


Netflix Growth Trend Line Chart


Top Countries Bar Chart


Ratings Distribution Chart


Release Year Histogram


Movies vs TV Shows Trend Graph



Conclusion
This project demonstrates how Exploratory Data Analysis helps uncover patterns and trends in large datasets. The Netflix dataset analysis provides insights into content distribution, growth, ratings, and production trends using effective visualizations.
