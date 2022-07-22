# PC Game Sales Study

Historical game sales data, user and expert ratings, genres and platforms (such as Xbox or PlayStation) are available from public sources. We need to identify the patterns that determine the success of the game. This will allow you to bet on a potentially popular product and plan advertising campaigns for the online store of computer games for the next year.

Description of the fields in the /datasets/games.csv file:
- Name - the name of the game
- Platform - platform
- Year_of_Release - year of release
- Genre - game genre
- NA_sales - sales in North America (millions of copies sold)
- EU_sales - sales in Europe (millions of copies sold)
- JP_sales - sales in Japan (millions of copies sold)
- Other_sales - sales in other countries (millions of copies sold)
- Critic_Score - Critics score (maximum 100)
- User_Score - user rating (maximum 10)
- Rating — rating from the ESRB (Entertainment Software Rating Board). This association determines the rating of computer games and assigns them an appropriate age category.

Composition of the study:
1. Data preparation:
    - Correction of types and gaps in values;
    - Calculation of total sales.
2. Exploratory data analysis:
    - Analysis of sales by platform, determination of relevant platforms and the current time period, data from which it makes sense to take into account;
    - Analysis of profit changes by platforms, identification of potentially profitable platforms;
    - Analysis of the impact of game ratings on sales within popular platforms;
    - Analysis of the distribution of games by genre, identifying profitable genres.
3. User portrait by region:
    - The most popular platforms;
    - The most popular genres;
    - The impact of the ESRB rating on sales in a particular region.
5. Hypothesis testing:
    - The average user ratings of the Xbox One and PC platforms are the same;
    - Average user ratings for Action and Sports genres are different.
    
   ## Tools/Libraries
   *Python, Pandas, Matplotlib, Seaborn, NumPy, SciPy, Hypotheses test*
