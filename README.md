# OTTs-Movie-Shows-Data-Preprocessing


Project Overview
This project focuses on preprocessing a large dataset of OTT movies and TV shows to analyze various features like release year, ratings, platform distribution, genre breakdown, and more. The dataset includes content from platforms like Netflix, Hulu, Amazon Prime, and Disney+ Hotstar. Several preprocessing steps and visualizations are performed to extract insights from the dataset.

Dataset
The dataset used in this project contains information about movies and TV shows across multiple OTT platforms. The following features are included:

Title
Director
Cast
Country
Date Added
Release Year
Rating
Duration
Genre (Listed In)
Type (Movie or TV Show)
Platform (Netflix, Hulu, Amazon Prime, Disney+ Hotstar)


Features and Functionality
1. Data Preprocessing
Duplicate Removal: The dataset is cleaned by removing duplicate entries.
Missing Values Handling: Any missing values are replaced with 0 to ensure data integrity.
Feature Engineering:
Duration is standardized by converting seasons to minutes.
Ratings are converted into numeric values for further analysis.
2. Data Analysis
Release Year Distribution: Visualization of the distribution of content release years, along with mean, median, and key release years across all platforms.
Platform-Specific Insights: A breakdown of the number of movies and shows available on each platform.
Genre Analysis: Exploration of the content genre across different OTT platforms using bar charts and word clouds.
Director Analysis: A list and visualization of the top 10 most prolific directors across all OTT platforms.
3. Visualizations
Bar Charts: Visual representation of content distribution by platform, type, genre, and rating.
Word Cloud: A word cloud is generated to represent the frequency of different genres across the dataset.
Top Directors: A bar chart displaying the top 10 directors based on the number of movies or shows they have directed across all platforms.
4. Library Dependencies
pandas: For data manipulation and preprocessing.
matplotlib: For data visualization.
seaborn: For advanced visualizations.
numpy: For numerical operations.
wordcloud: For generating word clouds.
collections: For counting genre occurrences.
Usage Instructions
1. Data Access
The dataset is stored in a CSV file on Google Drive. It can be mounted using Google Colab's drive.mount() function. Make sure the dataset is in the correct path as specified in the script.

2. Running the Script
Download or clone this repository.
Upload the dataset to your Google Drive or specify the path to your local dataset.
Run the script in a Jupyter Notebook or Google Colab.
3. Required Libraries
Install the required libraries using:

bash
Copy code
pip install pandas numpy matplotlib seaborn wordcloud
4. Visualizations
The script generates several bar plots, a distribution plot, and a word cloud to visualize the processed data. These plots include insights about:

Number of movies and shows by platform.
Genre distribution across different platforms.
Top 10 directors across platforms.
5. Key Steps in the Code
Data Cleaning: Handles duplicates, missing values, and incorrect data.
Data Transformation: Converts categorical features like ratings and duration into numerical values.
Data Visualization: Provides insights through various visualizations for better understanding.
Conclusion
This project provides a comprehensive analysis and preprocessing pipeline for a large dataset of OTT movies and shows. The analysis covers key aspects such as platform distribution, genre popularity, release trends, and director performance. The dataset can be expanded further for more in-depth analysis, or other features can be added. 
The implementation comes and can be more advance using various more architecture along with this visualization script. 



