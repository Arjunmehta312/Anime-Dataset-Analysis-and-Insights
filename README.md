## Anime Dataset Analysis and Insights

### Introduction
This project involves analysing a large dataset of anime shows. The dataset contains information about 18,495 anime shows, including details such as the name, type, release year, season, rating, voice actors, staff, and more.

### Objective
The main objective of this project is to derive meaningful insights from the dataset by performing various data analysis tasks. These tasks include analysing the distribution of ratings, release trends, the prevalence of voice actors and staff, and comparing different types of anime.

### Tools and Libraries Used
The project was carried out using Python, a popular programming language for data analysis. The following Python libraries were used:
Pandas: Used for data manipulation and analysis. It offers data structures and operations for manipulating numerical tables and time series.
Seaborn and Matplotlib: Used for data visualization. They provide a high-level interface for drawing attractive and informative statistical graphics.
Data Preprocessing
Before the analysis, the data was pre-processed to handle missing values and prepare it for analysis. Missing values in the ‘Voice_actors’ and ‘staff’ columns were filled with an empty string.

### Data Analysis and Insights Derived
In this project, a comprehensive analysis of a large dataset of anime shows was conducted. The analysis covered several aspects as follows:
Popularity and Ratings: Analysed the distribution of ratings to understand the average rating and determined how many anime shows fall above or below this average. Also identified the highest and lowest rated shows.
Release Trends: Examined the release years to identify any trends in the quantity and quality (ratings) of anime released over time. Additionally, analysed the release seasons to determine if more anime is released in a particular season.
Genre Analysis: Identified the most common genres/tags and investigated if there’s a correlation between certain genres and high ratings.
Content Warnings: Analysed the frequency and types of content warnings, providing insight into the maturity and themes of the anime in the dataset.
Studio Analysis: Identified which studios produce the most anime and investigated whether there’s a correlation between certain studios and high-quality (highly rated) anime.
Voice Actors and Staff: Examined which voice actors and staff members are most prevalent, and if their involvement has any correlation with the anime’s rating.
Type of Anime: Compared the different types of anime (TV, Web, etc.) in terms of quantity, ratings, and other factors.

### Conclusion
This project provided valuable insights into the world of anime and can serve as a foundation for further analysis or a recommendation system. The insights derived from this project could be useful for anime creators, distributors, and fans alike. The project demonstrated the power of Python and its libraries in handling, analysing, and visualizing large datasets.

### Future Work
There are many other potential analyses that could be performed on this dataset. For example, one could look at the relationship between the length of an anime and its rating, or analyse the popularity of different genres over time. Additionally, this analysis could be extended by incorporating additional data, such as user reviews or viewership numbers.

### Code Overview and Explanation
The Python code for this project includes the following steps:
Import necessary libraries
Load the dataset
Calculate the average rating and count how many shows have a rating above and below the average
Identify the highest and lowest rated shows
Plot a histogram, box plot, and violin plot of ratings
Plot the number of anime released each year and the average rating of anime released each year
Plot the number of anime released each season
Split the ‘Tags’ into separate genres and create a new dataframe
Plot the 10 most common genres
Calculate the average rating for each genre
Replace NaN values with an empty string
Split the ‘Content_Warning’ into separate warnings
Create a new dataframe with the count of each warning
Plot the 10 most common content warnings
Count the number of anime produced by each studio
Plot the 10 studios that produce the most anime
Calculate the average rating for each studio
Get the top 10 most prevalent individuals
Plot the count of the top 10 most prevalent individuals
Get the average ratings of the top 10 most prevalent individuals
Plot the average ratings of the top 10 most prevalent individuals
Load the data
Plot the quantity of each type of anime
Plot the average rating of each type of anime

### Requirements
You can install these libraries using pip:
pip install pandas seaborn matplotlib

### License
This project is licensed under the terms of the MIT license.
