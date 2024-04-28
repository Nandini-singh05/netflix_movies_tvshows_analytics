# NETFLIX MOVIES AND TV SHOWS ANALYTICS 📊 

This project is part of my data analyst portfolio, where I focused primarily on data visualization and exploratory data analysis (EDA). The goal was to explore a dataset of Netflix movies and TV shows to identify trends, insights, and patterns using various visualization techniques.

## Project Overview

The dataset used in this project contains information on all movies and TV shows available on Netflix, including details such as cast, directors, ratings, release year, duration, and other relevant metadata. It has 8807 rows and 12 columns.

### Installation:
- Clone this repository to your local machine.

- Install Dependencies and Setup :
  
  Install using requirements file provided -
  ```
  pip install -r requirements.txt
  ```

- Run the script.

### Steps Involved
To conduct the data analysis, I followed these steps:
* **Importing Libraries**: Imported essential Python libraries for data manipulation and visualization, including pandas, numpy, matplotlib, seaborn, missingno, and plotly.
* **Loading the Dataset**: Loaded the Netflix dataset into a pandas DataFrame to examine its structure, preview some records, and understand the various features available.
* **Data Exploration**: Gained a quick overview of the dataset, including the shape, feature types, and a basic understanding of the content.
* **Missing Values Analysis**:
  - Used missingno to visualize missing data as a matrix, bar chart, and heatmap to identify patterns of missingness.
  - Determined which columns had the most missing values and took appropriate action to address them.
* **Data Cleaning and Preprocessing**:
  - Dropped unnecessary columns (director and cast) with high missing values.
  - Filled or dropped rows with missing values in columns like country, date_added, rating, and duration.
  - Created new features, such as principal_country from country, year_added, and month_added from date_added.
  - Corrected data types, converting type and target_ages to categorical and year_added to numeric.
* **Feature Engineering**:
  - Created a new column target_ages based on the rating, categorizing content into different age groups.
  - Implemented other transformations to facilitate analysis.
* **Data Visualization and EDA**:
  - Content Proportion: Pie charts revealed movies dominate, comprising around two-thirds of Netflix content.
  - Rating Distribution: TV-MA emerged as the most common rating, suggesting a focus on mature audiences.
  - Growth Over Time: A rapid surge in movie content was observed from 2015 onwards.
  - Release Year Analysis: Movies peaked in 2018 and 2017, while TV shows peaked in 2020 and 2019.
  - Movie Duration: Most movies fall within the 85 to 120-minute range.
  - Top Genres and Countries: The United States leads in content production, with popular genres including "Drama," "Comedy," and "Action."
  - Word Clouds: Genre word clouds highlighted common terms like "Drama," "Comedy," and "Action."

---

### Key Findings
After completing the data visualization and EDA, the following insights emerged:
  1. Content Type Distribution: Nearly two-thirds of Netflix content consists of movies, while the rest are TV shows.
  2. Growth in Content: The addition of movies on Netflix has increased rapidly since 2015, with notable spikes in 2018 and 2019. TV show additions have been more consistent but grew substantially in 2020.
  3. Rating Distribution: The TV-MA rating is the most common for both movies and TV shows, indicating a focus on mature audiences. Movies primarily target teens and adults, while TV shows cater more to kids and teens.
  4. Release Years Analysis: Most movies on Netflix were released in 2017 and 2018, while most TV shows were released in 2019 and 2020.
  5. Movie Duration: The majority of Netflix movies have durations between 85 and 120 minutes.
  6. Top Genres: Popular genres for movies include "Drama," "Comedy," and "Action," while TV shows often feature "Kids," "Drama," and "Reality TV."
  7. Top Countries Producing Content: The United States is the leading producer of Netflix content, significantly outpacing other countries.

     
These insights demonstrate the evolving landscape of Netflix content and provide a comprehensive overview of its characteristics through data visualization and exploratory data analysis.

Feel free to contribute, report issues, or suggest improvements!✨



