# IMDb Movie Analysis Excel
IMDb Movie Analysis: Explore movie dataset, analyze using Excel to find success factors - director, genre, budget, ratings, and more.
## Problem Statement:
The dataset provided is related to IMDB Movies. A potential problem to investigate could be: "What factors influence the success of a movie on IMDB?" Here, success can be defined by high IMDB ratings. The impact of this problem is significant for movie producers, directors, and investors who want to understand what makes a movie successful to make informed decisions in their future projects.
## Excel project and Dashboard E05.xlsx
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
   
   ## Building an Excel Dashboard

Movie Performance Overview: Displays total movies, average IMDb score, and performance by rating. Genre Popularity: Provides insight into the financial success and volume of movies across different genres. Director & Star Analysis: Allows users to explore the top-performing directors and stars, with an option to view detailed portfolios. Financial Summary: Presents key financial metrics such as total gross earnings and profitability across movies. Dynamic Filters: Includes interactive slicers, dropdowns, and timeline controls to filter data by genre, director, year, and more.

![image](https://github.com/user-attachments/assets/b1d3ee31-e0df-41e5-8b74-02611e85a1c2)

![image](https://github.com/user-attachments/assets/51a2f7d9-18ed-4a06-bb10-2c35ffadd72a)



## Excel Features Used
Pivot Tables for dynamic analysis of budget, gross earnings, and movie count by genre. Conditional Formatting to highlight high-budget or high-grossing movies. Advanced Formulas such as VLOOKUP, INDEX-MATCH, and IF-STATEMENTS for calculating key metrics like profitability and average gross earnings. Data Visualizations: Bar charts, scatter plots, pie charts, and line charts to visualize data trends.

## Insights and Business Value
The analysis reveals valuable insights for Hollywood Insights Inc. and its clients, such as:

## Genre Trends:
Certain genres like Action and Adventure tend to generate higher box office revenue, while niche genres maintain steady audiences. Director Impact: Top directors consistently produce high-grossing movies, indicating the importance of directorial influence on box office success. Profitability Trends: Larger budgets do not always guarantee higher profitability, with many low-budget films yielding high returns. Seasonal Patterns: There are clear trends in the timing of movie releases, with certain months and seasons showing higher box office activity.

## How to Use
Download the movies.csv dataset from the repository. Open the provided Excel file that contains the analysis and dashboard. Interact with the dashboard by using slicers and dropdowns to explore different data perspectives. Review the analysis worksheets to dive deeper into the data behind the dashboard.
