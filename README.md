# Inferential_statistical_analysis_podcast
# Inferential Statistical Analysis of the Podcast Reviews <br>
## Objectives for this Part <br>
- Practice working with SQLite datasets.
- Practice performing EDA.
- Practice applying statistical inference procedures.
- Practice visualizing data with Matplotlib & Seaborn.
- Practice creating dashboards with Google Data Studio.
- Practice reading data, performing queries and filtering data using SQL and Pandas.<br>

The dataset can be dowloaded: https://www.kaggle.com/datasets/thoughtvector/podcastreviews/versions/28 <br>
The aim of this paper is to provide suggestions on what features would be needed to make the podcast attractive to listeners and attract the largest possible target audience. To achieve this goal, the podcast feedback database will be analysed and recommendations will be made on the basis of its answers. In addition, hypotheses will be put forward:<br>

* Hypothesis: is there any significant difference between podcasts groups ratings: single episodes vs. serial episodes?
* Hypothesis: is there a difference between the length of the best rating feedback and the worst rating?
## Used Libraries:
collections.defaultdict; 
pandas; 
sqlite3; 
matplotlib.pyplot; 
numpy; 
re; 
seaborn; 
scipy.stats

## Conclusions:
The main objective of this work is to show what characteristics a popular podcast should have. The period of our study is 2005-2023, the total information provided is 110024 names of the shows, for which 2043297 reviews were given. The annual distribution of the feedback shows that the highest listener activity was in the years 2019-2022. This activity coincides with the period of the COVID-19 pandemic, which may have had an impact on the popularity of this type of entertainment. The impact of crises has not been studied, but such a study would be interesting in the future.
* The number of reviews a podcast would have to have in order to be considered popular should be examined. Most of the podcasts have 1-2 reviews, which hardly defines popularity. The chosen method of calculation shows that having 317 or more reviews would guarantee the popularity of the podcast in terms of viewer response. This number of reviews is available for 1% of all available programmes.
* An attempt to divide the podcasts into single episode and serial episode groups, based on the available data, reveals that single episode programmes are the most popular. This raises the hypothesis whether there is a difference between the ratings of series and one-episode podcasts, and whether this average of the ratings is statistically significant. The t-test used, with 95% confidence, shows that this difference is statistically significant and reveals the advantage of single programmes over series programmes. 
* When comparing the distribution of reviews, it is observed that the vast majority of podcasts have the highest rating, following lowest rating. This raises the hypothesis whether there is a statistically significant difference in the length of reviews between these rating groups. The calculation shows with 95% confidence, that the difference is statistically significant and that the length of the review in the worst-rated podcasts is higher than in the best-rated podcasts. This could be explained by the listener trying to justify in detail his bad rating, which could also be useful for the evaluation of the show: the time spent on such a description is also valuable.
* Finally, the most popular podcasts with the highest response rates are in educational, religious-spiritual and crime theme categories.
