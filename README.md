# Cognify_Data-Analysis_Internship-tasks

Cognify Internship – Restaurant Data Analysis
Project Overview

This project focuses on analyzing a restaurant dataset to extract actionable insights about ratings, cuisines, geographic distribution, restaurant chains, reviews, votes, and service offerings. The analysis is structured across Level 2 and Level 3 tasks, with a combination of data cleaning, visualization, and statistical analysis.

Dataset

Columns include:
Restaurant ID, Restaurant Name, Country Code, City, Address, Locality, Locality Verbose, Longitude, Latitude, Cuisines, Average Cost for two, Currency, Has Table booking, Has Online delivery, Is delivering now, Switch to order menu, Price range, Aggregate rating, Rating color, Rating text, Votes

Data types include numerical, categorical, and text.

Level 2 Tasks
Task 1: Restaurant Ratings

Objective: Analyze the distribution of aggregate ratings and calculate the average number of votes.

Key Steps:

Inspect Aggregate rating and Votes columns.

Handle missing or invalid values.

Visualize rating distribution using histograms.

Determine the most common rating range.

Calculate average number of votes per restaurant.

Optional: Categorize ratings (Excellent, Good, Average, Poor) for better visualization.

Task 2: Cuisine Combination

Objective: Identify common cuisine combinations and evaluate if certain combinations have higher ratings.

Key Steps:

Inspect Cuisines column and handle missing values.

Split multiple cuisines and count most common combinations.

Compute average rating for each cuisine combination.

Visualize top 10 cuisine combinations by average rating using bar charts.

Task 3: Geographic Analysis

Objective: Plot restaurant locations on a map and identify clusters.

Key Steps:

Inspect Longitude and Latitude columns.

Remove missing coordinates.

Visualize locations with scatter plots using Matplotlib/Seaborn.

Optional: Use Folium to create interactive maps and clusters.

Identify high-density areas or clusters using KDE plots or KMeans clustering.

Task 4: Restaurant Chains

Objective: Identify restaurant chains and analyze their ratings and popularity.

Key Steps:

Identify restaurants with multiple outlets (Restaurant Name appearing >1).

Compute average rating, total votes, and number of outlets for each chain.

Visualize top chains by rating and popularity.

Optional: Scatter plot ratings vs votes, with marker size representing number of outlets.

Level 3 Tasks
Task 1: Restaurant Reviews

Objective: Analyze text reviews to extract insights and relationships with ratings.

Key Steps:

Inspect and clean Rating text column.

Separate positive (rating ≥4) and negative (rating ≤2) reviews.

Identify most common keywords in positive and negative reviews.

Generate WordClouds for visual representation.

Calculate average review length (words).

Explore correlation between review length and ratings with scatter plots.

Task 2: Votes Analysis

Objective: Identify restaurants with highest and lowest votes and analyze correlation with ratings.

Key Steps:

Inspect Votes and Aggregate rating columns.

Handle missing values.

Identify top 5 and bottom 5 restaurants by votes.

Compute correlation between votes and ratings.

Visualize relationship using scatter plots.

Optional: Apply log transformation to handle outliers in votes.

Task 3: Price Range vs Online Delivery & Table Booking

Objective: Analyze whether higher-priced restaurants offer more services.

Key Steps:

Inspect Price range, Has Online delivery, Has Table booking.

Convert Yes/No columns to numeric (1/0).

Group by Price range to compute proportion of restaurants offering services.

Visualize trends using bar charts.

Optional: Combine both services in a single comparative chart.

Calculate correlation between price range and availability of services.

Tools & Libraries

Python Libraries: pandas, numpy, matplotlib, seaborn, wordcloud, sklearn (for clustering), folium (optional interactive maps).

Key Visualizations: Bar charts, scatter plots, histograms, KDE plots, WordClouds, interactive maps.

Insights

Distribution and trends in ratings highlight high-performing restaurants.

Cuisine combinations influence ratings and popularity.

Geographic clustering identifies restaurant density patterns.

Chains analysis shows correlations between outlets, ratings, and popularity.

Reviews analysis highlights common positive and negative keywords and correlation with review length.

Votes analysis shows popularity patterns and relationship with ratings.

Price range vs services identifies if premium restaurants provide more offerings.

How to Run

Install required Python packages:

pip install pandas matplotlib seaborn wordcloud folium scikit-learn


Load the dataset in pandas.

Run the Python scripts for each task sequentially.

Visualizations will appear inline in Jupyter or saved as image/HTML files.


Author:
Jenifer Shalika S
Data Analyst Trainee
