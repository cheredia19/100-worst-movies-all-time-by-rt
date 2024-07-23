---
title: 'The 100 worst movies of all time'
description: 'Insight of the 100 movies that got the worst critics on Rotten Tomatoes'
---

*By [César Heredia](https://x.com/cahered), data journalist*

The film **Ballistic: Ecks vs. Sever**, starring Antonio Banderas and Lucy Liu, is labeled the **worst movie of all time** by *Rotten Tomatoes*, an American review website for films and TV shows. The action movie, released in 2022, got a critic score of 0% and an audience score of 20%.

It received **119 critics** from September 18, 2022, to September 19, 2022, although most came 22 years ago. All of the critics were **negative**.

The horror movie **One Missed Call** (2008), and Nicolas Cage's **Left Behind** (2014) complete the unwanted podium.

## Has the quality of the films declined over time?

The 2000s decade gathered 46% of the 100 worst movies, followed by the 2010s (28%). 

<PlotlyBarChart
  data={{
    url: 'decade.csv'
  }}
  title="Decade of release"
  xAxis="decade"
  yAxis="amount"
/>

<PlotlyLineChart
  data={{
    url: 'year.csv'
  }}
  title="Year of release"
  xAxis="year"
  yAxis="rate"
/>

<PlotlyBarChart
  data={{
    url: 'critic_scores.csv'
  }}
  title="Most repeated critic scores"
  xAxis="critic_score"
  yAxis="amount"
/>

<PlotlyLineChart
  data={{
    url: 'audience_score.csv'
  }}
  title="Most repeated audience scores (/100)"
  xAxis="audience_score"
  yAxis="amount"
/>

<PlotlyBarChart
  data={{
    url: 'critic_movie.csv'
  }}
  title="Number of critics for each movie"
  xAxis="movie"
  yAxis="reviews"
/>

<PlotlyBarChart
  data={{
    url: 'critic_publications.csv'
  }}
  title="Number of critics for each publication"
  xAxis="publicationName"
  yAxis="publications"
/>

<PlotlyBarChart
  data={{
    url: 'all_critics.csv'
  }}
  title="Number of reviews made by each critic"
  xAxis="criticName"
  yAxis="reviews"
/>

<PlotlyBarChart
  data={{
    url: 'all_critics.csv'
  }}
  title="Number of reviews made by each critic (rate)"
  xAxis="criticName"
  yAxis="rate"
/>

## List of the 100 worst movies of all time

<FlatUiTable
  data={{
    url: 'movies.csv'    
  }}
/>

## All the reviews of these films

<FlatUiTable
  data={{
    url: 'all_reviews.csv'    
  }}
/>
