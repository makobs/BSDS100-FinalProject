# [BSDS100](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021.git) - Final Project
## David Chung & Mia Kobayashi<br/>Professor Michael Ruddy<br/>17 May 2021

Dataset taken from [Kaggle](https://www.kaggle.com/).
We specifically looked at the [IMDb Movies Extensive Dataset](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset) that includes 85,855 movies from 1874 to planned movies released in 2027.
The dataset from Kaggle included 4 files, a movies, ratings, a names, and a title principals dataset.

For this project, we only chose to look at the movies dataset as it included attributes like movie title and title id, average rating, number of votes, genre (up to 3), year and date of release, the country the movie was produced in, budget, etc.  And the other datasets didn’t have information that was pertinent to the analyzations we wanted to perform.



## Analyzations
**The Comparison** | **Hypothesis** | **Hypothesis Supported / Rejected**
--- | --- | ---
[Country vs. Total Number of Movies Produced](https://github.com/makobs/BSDS100-FinalProject/blob/d97cd25445520dc71cbcf6961dcca7be3b56c753/1%20-%20Country%20v.%20Total%20Number%20of%20Movies%20Produced.ipynb) | The USA will be the country that makes the most movies, with European countries following suit, then Asian. | Partially supported -- USA did make the most movies.
[Time vs. Movie Ratings](https://github.com/makobs/BSDS100-FinalProject/blob/d97cd25445520dc71cbcf6961dcca7be3b56c753/2%20-%20Time%20v.%20Movie%20Ratings.ipynb) | Movie ratings, on average, have gotten better as time went on. | Rejected -- movie ratings got worse as time went on.
[Time vs. Movie Budget](https://github.com/makobs/BSDS100-FinalProject/blob/d97cd25445520dc71cbcf6961dcca7be3b56c753/3%20-%20Time%20v.%20Movie%20Budget.ipynb) | The budget (in USD, regardless of country) that is spent on movie productions will remain relatively constant over the years. | Rejected -- budget substantially increased.
[Budget vs. US Gross Income in the U.S.](https://github.com/makobs/BSDS100-FinalProject/blob/d97cd25445520dc71cbcf6961dcca7be3b56c753/4%20-%20Budget%20v.%20US%20Gross%20Income%20in%20the%20U.S..ipynb) | The higher the budget of the movie is, the more gross income in the U.S. the movie will have collected. | Supported.
[Budget, Metascore, Average Vote vs. Gross Income in the U.S.](https://github.com/makobs/BSDS100-FinalProject/blob/d97cd25445520dc71cbcf6961dcca7be3b56c753/5%20-%20Budget,%20Metascore,%20Average%20Vote%20v.%20Gross%20Income%20in%20the%20U.S..ipynb) | Budget, metascore, and avg vote together will be good predictors of gross income produced in the U.S.  The binary classification model will be more effective than the linear regression model. | Supported.
[Duration vs. Genre](https://github.com/makobs/BSDS100-FinalProject/blob/d97cd25445520dc71cbcf6961dcca7be3b56c753/6%20-%20Duration%20v.%20Genre.ipynb) | Movies with the genre of history, biography, and war will have the longest durations because these generally have more complex plots. Animation will have the shortest duration because these usually have light plots and are more for entertainment. | Supported.
[Genre vs. Average Vote](https://github.com/makobs/BSDS100-FinalProject/blob/d97cd25445520dc71cbcf6961dcca7be3b56c753/7%20-%20Genre%20v.%20Average%20Vote.ipynb) | Biographies and drama will have the highest average vote score while adult and comedy will have the lowest avg vote score. | Partially supported -- adult films had the lowest score.
[Average Vote vs. Metascore](https://github.com/makobs/BSDS100-FinalProject/blob/d97cd25445520dc71cbcf6961dcca7be3b56c753/8%20-%20Average%20Vote%20v.%20Metascore.ipynb) | As the average vote increases, so will the metascore. | Supported.

For all analyzations, click [here]().

## Closing Remarks
We chose this dataset because we thought that we'd find useful relationships between the variables with the addition of finding movies to be an interesting topic and something that a lot of people watch -- we wanted to see if there were correlations between the given data.  

Top 2 Intresting trends / finds within the data:
- When comparing the average rating by month, for all the years combined, it was interesting to see that some months “performed” better or had higher ratings than others, specifically the late fall / early winter months.
- When comparing the average vote in relation to the metascore, the relationship between the two variables was more linear than expected as we personally feel that critics don't always agree with the masses.
