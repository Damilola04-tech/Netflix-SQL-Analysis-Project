📊 Netflix SQL Analysis Project
📌 Overview

This project explores Netflix’s content catalog using PostgreSQL. The goal is to analyze movies and TV shows across different attributes such as ratings, release years, countries, directors, genres, and descriptions. The queries answer key business questions about Netflix’s content library and provide insights into trends, patterns, and distributions.

🗂️ Dataset Structure

The dataset is stored in a single table:

Table: netflix

show_id – Unique identifier

type – Movie or TV Show

title – Name of the content

director – Director(s)

casts – Cast members

country – Country of production

date_added – Date added to Netflix

release_year – Year released

rating – Content rating (e.g., PG, TV-MA)

duration – Length (minutes for movies, seasons for TV shows)

listed_in – Genres/categories

description – Content description

🔎 SQL Tasks Performed
1. Content Distribution

Count of movies vs. TV shows.

2. Most Common Ratings

Identifies the most frequent rating per content type.

3. Movies by Year

Lists all movies released in a given year (e.g., 2020).

4. Top 5 Countries

Finds countries producing the most Netflix content.

5. Longest Movie

Retrieves the longest movie by duration.

6. Recent Content

Lists content added in the last 5 years.

7. By Director

Finds all content directed by a specific director (e.g., Rajiv Chilaka).

8. Multi-Season TV Shows

Lists TV shows with more than 5 seasons.

9. Genre Analysis

Counts number of content items in each genre.

10. India Releases

Calculates yearly releases from India and top 5 years with highest average share.

11. Documentaries

Lists all movies categorized as documentaries.

12. Missing Directors

Identifies content with no listed director.

13. Actor Analysis

Finds movies with Salman Khan in the last 10 years.

14. Top Indian Actors

Lists top 10 actors by number of appearances in Indian movies.

15. Content Categorization

Flags content as “Bad” if descriptions contain “kill” or “violence”, otherwise labels as “Good”.

Counts distribution of “Good” vs. “Bad” content by type.

🚀 Tools & Technologies

SQL (PostgreSQL) – Data analysis & querying

Netflix Dataset – Publicly available dataset used for exploration

📈 Key Insights

Netflix content is dominated by Movies, but TV shows are steadily increasing.

TV-MA and TV-14 are among the most common ratings.

India is a top producer of Netflix content, with key years showing spikes in releases.

A significant amount of content has no director data, showing metadata gaps.

Certain actors and directors have repeatedly contributed to Netflix’s catalog.

Keyword analysis highlights how Netflix balances “Good” vs. “Bad” themes in descriptions.

📚 Learning Outcomes

Through this project, you can:

Practice SQL aggregation, window functions, string operations, and date handling.

Learn how to unpack multi-valued columns using UNNEST.

Build insights from real-world datasets by asking practical business questions.

📌 Next Steps

Extend queries with CTEs and subqueries for deeper insights.

Build dashboards in Power BI or Tableau using the query results.

Automate reporting with Python + SQL integration.

✨ This project demonstrates how SQL can transform raw datasets into meaningful insights about media trends and business decisions.# Netflix-SQL-Analysis-Project
Analyzed Netflix’s catalog using SQL to uncover insights on movies and TV shows. Queries explored content by type, rating, country, genre, directors, and actors. Applied window, string, and date functions to find trends, top contributors, and categorize content themes.
