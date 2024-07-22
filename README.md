---
title: 'The 100 worst movies of all time'
description: 'Insight of the 100 movies that got the worst critics on Rotten Tomatoes'
---

*By [César Heredia](https://x.com/cahered), data journalist*


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
    url: 'critic_publications.csv'
  }}
  title="Number of reviews made by each critic"
  xAxis="criticName"
  yAxis="reviews"
/>

<PlotlyBarChart
  data={{
    url: 'critic_publications.csv'
  }}
  title="Number of reviews made by each critic"
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
