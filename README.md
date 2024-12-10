# netflix_titles-EDA
Exploratory Data Analysis (EDA) on Netflix Titles Dataset
Project Overview
This project performs Exploratory Data Analysis (EDA) on a dataset of Netflix titles to gain insights into the types of content available, the distribution of ratings, and trends in the release years of movies and TV shows. The dataset includes information on the titles, genres, ratings, countries of origin, and release years of Netflix content.

The primary goal of this analysis is to uncover patterns related to Netflix’s content offerings, including the most popular types of content, the distribution of ratings, and how the content varies across different countries and years.

Dataset Description
The dataset, netflix_titles.csv, contains the following columns:

show_id: Unique identifier for the show.
type: Type of content (Movie or TV Show).
title: Title of the movie or TV show.
director: Director of the content.
cast: Cast of the content.
country: Country of origin.
date_added: Date the content was added to Netflix.
release_year: Year the content was released.
rating: Rating of the content (e.g., PG, TV-MA).
duration: Duration of the movie or TV show.
genre: Genre of the content (e.g., Drama, Comedy).
description: Short description of the content.
Goals of the Exploration
Content Distribution: Analyze the distribution of movies and TV shows on Netflix.
Content Ratings: Explore how different types of content are rated and their popularity.
Release Year Trends: Investigate trends in content release years to identify how Netflix's offerings have evolved over time.
Genre Analysis: Understand the most common genres available on Netflix and their distribution.
Missing Data: Handle missing data for columns like director, cast, and country to improve the dataset’s completeness.
Key Insights
Most Popular Content Type:

The majority of the content on Netflix is Movies (88%), while TV Shows make up only a smaller percentage (12%).
Content Ratings:

The most frequent ratings are TV-MA, PG-13, and TV-14, with TV-MA being the most common rating for both movies and TV shows.
Release Year Trends:

There is a clear trend in the increase of Netflix content starting from the early 2000s, with a significant spike around 2010 and beyond, marking the rise of original content production on Netflix.
Genre Distribution:

Dramas are the most common genre on Netflix, followed by genres like Comedies and Documentaries.
Missing Data:

A significant number of records have missing director, cast, and country values, which were handled by filling in missing values with default or placeholder values (e.g., "Missing").
Visualizations
This project features various visualizations to better understand the dataset:

Donut Chart: To show the distribution of Movies vs. TV Shows on Netflix.
Bar Plot: To visualize the distribution of ratings across content.
Pie Chart: To visualize the breakdown of content by rating type.
Scatter Plot: To explore relationships between content duration and release year.
Line Chart: To track the number of content releases over the years.
Data Cleaning and Transformation
Handling Missing Data: Missing values in columns like director, cast, and country were handled appropriately by dropping rows or filling with placeholders.
Feature Engineering:
A new column, year_added, was created to extract the year when the content was added to Netflix.
The date_added column was transformed to datetime format for easier analysis.
The listed_in column was renamed to genre, and each content's genre was simplified to the first listed genre.
Technologies Used
Python: Main programming language.
Pandas: For data manipulation and analysis.
Matplotlib & Seaborn: For creating visualizations.
Plotly: For interactive and aesthetically pleasing charts.
NumPy: For numerical operations and handling large datasets.
How to Use
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/netflix-titles-eda
cd netflix-titles-eda
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the EDA:
bash
Copy code
jupyter notebook Netflix_EDA.ipynb
This will open the Jupyter notebook where you can explore the analysis, visualizations, and insights.
Future Work
Content Prediction: Using machine learning to recommend content based on users' viewing habits.
Sentiment Analysis: Analyzing the description column to gauge sentiment and correlate it with ratings and popularity.
Genre Trend Analysis: Investigating how genre trends have evolved over time on Netflix.
Results
This analysis provides insights into the Netflix library's evolution, rating distribution, and most popular genres, offering valuable information for content creators and viewers alike.

