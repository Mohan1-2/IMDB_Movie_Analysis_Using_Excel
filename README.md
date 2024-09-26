# IMDB_Movie_Analysis_Using_Excel
IMDb Movie Analysis: Explore movie dataset, analyze using Excel to find success factors - director, genre, budget, ratings, and more.
## Problem Statement:
The dataset provided is related to IMDB Movies. A potential problem to investigate could be: "What factors influence the success of a movie on IMDB?" Here, success can be defined by high IMDB ratings. The impact of this problem is significant for movie producers, directors, and investors who want to understand what makes a movie successful to make informed decisions in their future projects.
### **Data Source:**

[movies.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/b6a256a5-ab42-4e44-a91a-c9ec379d5eef/movies.csv)

The "movies.csv" file contains data about various movies. Here's an overview of its structure and the type of data it includes:

1. **name**: Movie name (String)
2. **rating**: Movie rating (String)
3. **genre**: Genre of the movie (String)
4. **year**: Year of release (Integer)
5. **released**: Release date (String, includes country)
6. **score**: IMDb score (Float)
7. **votes**: Number of votes on IMDb (Float)
8. **director**: Director's name (String)
9. **writer**: Writer's name (String)
10. **star**: Main star's name (String)
11. **country**: Country of origin (String)
12. **budget**: Production budget (Float)
13. **gross**: Gross earnings (Float)
14. **company**: Production company (String)
15. **runtime**: Runtime in minutes (Float)
    ### **TASKS:- Excel Data Analysis: Manipulation, Formulas and Functions**

   **Missing Data Handling:** Identify and address missing data in the movies dataset. Are there any patterns in the missing data that can be noted?
   
   **Data Sorting and Filtering:** Sort the movies by year of release and by gross earnings. Then, filter the dataset to show only movies with an IMDb score greater than 8.0.
   
   **Analysis of Movie Genres:** Analyze the distribution of movies across different genres. Which genre has the most movies, and which has the least?
   
   **Budget and Gross Earnings Comparison:** Compare the budget and gross earnings of movies. Create a scatter plot to visualize if there's a correlation between them.
   
   **IMDb Score Categorization:** Categorize movies into 'High', 'Medium', and 'Low' based on their IMDb scores. Define the thresholds for these categories.
   
   **Country-wise Movie Production:** Analyze which countries have produced the most movies. Create a pie chart to represent this data
   
   **Director Analysis:** Who are the top 5 directors with the highest average gross earnings? Use formulas to calculate and sort this information.
   
   **Runtime Analysis:** Calculate the average runtime of movies. How does this vary across different genres?
   
   **Top Grossing Movies by Year:** Identify the top grossing movie of each year in the dataset.
   
   **Rating Popularity Over Time:** Analyze how the popularity of different movie ratings (G, PG, PG-13, R, etc.) has changed over the years.
   
   **Conditional Formatting for High Budget Movies:** Use conditional formatting to highlight movies with budgets above a certain threshold.
   ### **Building an Excel Dashboard**

Develop a comprehensive and interactive Excel dashboard that integrates key metrics and insights derived from the "movies.csv" dataset. The dashboard should provide a holistic view of the movie industry trends, focusing on movie performance, genre popularity, director and star impact, and financial analysis of movie earnings.

### **Key Elements to Include:**

1. **Movie Performance Overview**:
    - Display key metrics like total number of movies, average IMDb score, and distribution of movies by rating. Include a breakdown of movies by decade.
2. **Genre Popularity Tracker**:
    - Include metrics such as the number of movies per genre, average gross earnings by genre, and a ranking of genres based on popularity and financial success.
3. **Director and Star Analysis Panel**:
    - Visualize key data points such as top directors and stars based on average gross earnings and IMDb scores. Include a feature to select a director or star to view their movie portfolio.
4. **Financial Analysis of Movies**:
    - Create a financial summary showing total gross earnings, average budget, and profitability of movies. Include a comparison of budget versus gross earnings for top-performing movies.
5. **Interactive Features**:
    - Implement slicers, dropdowns, and timeline controls to allow users to filter data across different dimensions (e.g., time periods, genres, directors, stars). Ensure functionality for dynamic interaction with the data.

