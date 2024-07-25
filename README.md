---
title: 'The 100 worst movies of all time'
description: 'Insight of the 100 movies that got the roughest reviews on Rotten Tomatoes'
---

*By [César Heredia](https://x.com/cahered), data journalist*

The film **Ballistic: Ecks vs. Sever**, starring Antonio Banderas and Lucy Liu, is labeled the **worst movie of all time** by Rotten Tomatoes, an American review website for films and TV shows. This action movie, released in 2022, got a critic score of 0% over 119 reviews, and an audience score of 20% (+10,000 ratings).

The horror movie **One Missed Call** (2008), and Nicolas Cage's **Left Behind** (2014) complete the unwanted podium.

One Missed Call, a movie that addresses the question *what will it sound like when you die?*, received an audience score of 29% and 80 negative reviews from critics, while Left Behind: The End Begins got 19% and 70, respectively.

## Has the quality of the films declined over time?

The 2000s decade gathered 46% of the 100 worst movies, followed by the 2010s (28%). This group includes the *classic* cable TV film Jack and Jill (2011), the horror-satire Scary Movie V (2013) with Charlie Sheen and Ashley Tisdale, and Texas Rangers (2021), a movie that saw James Van Der Beek and Ashton Kutcher in different roles from the ones they cast in TV shows Dawson's Creek and That 70s Show.

<PlotlyBarChart
  data={{
    url: 'decade.csv'
  }}
  title="Decade of release"
  xAxis="decade"
  yAxis="amount"
/>

The year 2002 itself recorded 10% of the worst-evaluated movies by critics and audiences on Rotten Tomatoes. Apart from the mentioned  *Ballistic: Ecks vs. Sever*, films like **Pinocchio**, written and cast by Roberto Benigni (La vita è bella), romance story **Killing Me Softly**, and Dana Carvey's (Wayne's World) **The Master of Disguise**, among others, were the films released that year that made the list. Seven movies from 2007 and 2016 were deemed into the group of the worst ones of all time.

<PlotlyLineChart
  data={{
    url: 'year.csv'
  }}
  title="Year of release"
  xAxis="year"
  yAxis="rate"
/>

Thirty-five films were rated with the lowest allowed (0%), while twenty-two movies received a critic score (a.k.a. Tomatometer) of 3%.

<PlotlyBarChart
  data={{
    url: 'critic_scores.csv'
  }}
  title="Most repeated critic scores (%)"
  xAxis="critic_score"
  yAxis="amount"
/>

The audience from Rotten Tomatoes rated the *worst 100 films* within a range between 11 and 76 percent. 25, 29, and 38 scores repeated six times each. The one with 76%? **Freelance**. An action movie, released in 2023 and starring John Cena, Allison Brie, Christian Slater, and Colombian actor Juan Pablo Raba, gathered the number over +100 verified ratings.

To put it in perspective, the maximum possible critic and audience scores are 100%.

<PlotlyLineChart
  data={{
    url: 'audience_score.csv'
  }}
  title="Most repeated audience scores (%)"
  xAxis="audience_score"
  yAxis="amount"
/>

The full list of Rotten Tomatoes' 100 Worst Movies of All Time is below. You can filter by ranking, title, year of release, plus critic and audience scores.

<FlatUiTable
  data={{
    url: 'movies.csv'    
  }}
/>

## Insight of the reviews

Of the so-called *100 worst movies of all time*, the action and adventure film **The Last Airbender (2010)** got the most reviews by critics: 183 negative, and only nine positive.

"It captivated my imagination," said Fred Topel, from Can Magazine, while Felix Vasquez Jr. (Cinema Crazed) was "intrigued to see where the next film goes (at the time),"  were two of the positive ones.

At the other end, **Simon Sez** (1999), cast by former Chicago Bulls player Dennis Rodman, needed only 20 critic reviews to earn its place in the worst 100.

"If you're a big Dennis Rodman fan, watch him playing basketball. If you're not, then you have zero reason to take in this movie," argued Evan Gatehouse, from Apollo Guide.

The number of reviews received by each film can be seen in the graph below:

<PlotlyBarChart
  data={{
    url: 'critic_movie.csv'
  }}
  title="Number of reviews for each movie"
  xAxis="movie"
  yAxis="reviews"
/>

Variety (93), The New York Times (87), and Los Angeles Times (74) were the publications that posted more reviews.

<PlotlyBarChart
  data={{
    url: 'critic_publications.csv'
  }}
  title="Number of reviews for each publication"
  xAxis="publicationName"
  yAxis="publications"
/>

One particular name stood out from the film pundits: **Brian Orndorf**. He posted 70 reviews on six different websites. Orndorf is followed by **Frank Swietek** (56 reviews), and **Eric D. Snider** (49 collaborations) among the most active critics who posted reviews on the worst 100 movies).

<PlotlyBarChart
  data={{
    url: 'all_critics.csv'
  }}
  title="Number of reviews made by each critic"
  xAxis="criticName"
  yAxis="reviews"
/>

All the reviews of the Rotten Tomatoes' 100 Worst Movies of All Time are below. Remember that you can filter by date, critic name, critic page URL, whether is or not a top critic, publication URL on RT, publication name, review URL, quotes, score sentiment, original score ,and, of course, by movie.

<FlatUiTable
  data={{
    url: 'all_reviews.csv'    
  }}
/>
