# IMDb-Movie-Analysis

## Description:

### Problem Statement: 
> The dataset provided is related to IMDB Movies. A potential problem to investigate could be: "What factors influence the success of a movie on IMDB?" Here, success can be defined by high IMDB ratings. The impact of this problem is significant for movie producers, directors, and investors who want to understand what makes a movie successful to make informed decisions in their future projects.

### Data Cleaning: 
> This step involves preprocessing the data to make it suitable for analysis. It includes handling missing values, removing duplicates, converting data types if necessary, and possibly feature engineering.

### Data Analysis: 
> Here, you'll explore the data to understand the relationships between different variables. You might look at the correlation between movie ratings and other factors like genre, director, budget, etc. You might also want to consider the year of release, the actors involved, and other relevant factors.

### Five 'Whys' Approach: 
> This technique will help you dig deeper into the problem. For instance, if you find that movies with higher budgets tend to have higher ratings, you can ask "Why?" repeatedly to uncover the root cause. Here's an example:

> Q: "Why do movies with higher budgets tend to have higher ratings?"

> A: They can afford better production quality.

> Q: "Why does better production quality lead to higher ratings?"

> A: It enhances the viewer's experience.

> Q: "Why does an enhanced viewer experience lead to higher ratings?"

> A: Viewers are more likely to rate a movie highly if they enjoyed watching it.

> Q: "Why are viewers more likely to rate a movie highly if they enjoyed watching it?"

> A: Positive experiences lead to positive reviews.

> Q: "Why do positive reviews matter?"

> A: They influence other viewers' decisions to watch the movie, increasing its popularity and success.

### Data Analytics Tasks:
#### A- Cleaning the data: 
> This is one of the most important step to perform before moving forward with the analysis. Use your knowledge learned till now to do this. (Dropping columns, removing null values, etc.)

> task: Clean the data

#### B- Movies with highest profit: 
> Create a new column called profit which contains the difference of the two columns: gross and budget. Sort the column using the profit column as reference. Plot profit (y-axis) vs budget (x- axis) and observe the outliers using the appropriate chart type.

> task: Find the movies with the highest profit?

#### C- Top 250: 
> Create a new column IMDb_Top_250 and store the top 250 movies with the highest IMDb Rating (corresponding to the column: imdb_score). Also make sure that for all of these movies, the num_voted_users is greater than 25,000. Also add a Rank column containing the values 1 to 250 indicating the ranks of the corresponding films.

> Extract all the movies in the IMDb_Top_250 column which are not in the English language and store them in a new column named Top_Foreign_Lang_Film. You can use your own imagination also!

> task: Find IMDB Top 250

#### D- Best Directors: 
> TGroup the column using the director_name column.
Find out the top 10 directors for whom the mean of imdb_score is the highest and store them in a new column top10director. In case of a tie in IMDb score between two directors, sort them alphabetically.

> task: Find the best directors

#### E- Popular Genres:
> Perform this step using the knowledge gained while performing previous steps.

> task: Find popular genres

#### F- Charts: 
> Create three new columns namely, Meryl_Streep, Leo_Caprio, and Brad_Pitt which contain the movies in which the actors: 'Meryl Streep', 'Leonardo DiCaprio', and 'Brad Pitt' are the lead actors. Use only the actor_1_name column for extraction. Also, make sure that you use the names 'Meryl Streep', 'Leonardo DiCaprio', and 'Brad Pitt' for the said extraction.

> Append the rows of all these columns and store them in a new column named Combined.

> Group the combined column using the actor_1_name column.

> Find the mean of the num_critic_for_reviews and num_users_for_review and identify the actors which have the highest mean.

> Observe the change in number of voted users over decades using a bar chart. Create a column called decade which represents the decade to which every movie belongs to. For example, the title_year year 1923, 1925 should be stored as 1920s. Sort the column based on the column decade, group it by decade and find the sum of users voted in each decade. Store this in a new data frame called df_by_decade.

> task: Find the critic-favorite and audience-favorite actors.
