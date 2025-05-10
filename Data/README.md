| Field       | Type    | Description                                         |
|-------------|---------|-----------------------------------------------------|
| Rank        | Numeric | Movie rank on IMDb Top 250 Movies                  |
| Movie Title | Text    | Movie title                                        |
| Wins        | Numeric | Amount of awards won by movie                      |
| Nominations | Numeric | Amount of award nominations by movie               |
| year        | Numeric | Year the movie was made                            |
| rating      | Text    | Movie rating (e.g., PG, PG-13, R)                  |
| genre       | Text    | Movie genre (e.g., Action, Drama, Comedy)          |
| score       | Numeric | IMDb user score out of 10 (as of 2021)             |
| votes       | Numeric | Number of IMDb user scores                         |
| country     | Text    | Country the movie was released from                |
| budget      | Numeric | The budget of the movie                            |
| gross       | Numeric | Gross revenue of the movie                         |
| company     | Text    | Production company                                 |
| runtime     | Numeric | Length in minutes of the movie                     |

The dataset chosen from Kaggle named "Movie Industry" by Daniel Grijalva has extensive information on thousands of movies from 1980 to 2020.  
[📄 Download the Movies CSV](https://github.com/user-attachments/files/20030882/movies.csv)

The additional information gathered came from IMDbs Top 250 Movies list. Each movie's link was crawled through and the amount of awards the movie won and was nominated for were scraped and added to a dataframe with the movie's name and release year.  
[🔗 IMDb Top 250 Movies](https://www.imdb.com/chart/top/?ref_=nv_mv_250)

The two dataframes were then merged on "Movie Title" and "year". The csv below is the merged dataframe that was used to start the code for all analysis questions.   
[📄 Download the Merged CSV](https://github.com/user-attachments/files/20137291/juroe_project_proposal.csv)
