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

<PlotlyLineChart
  data={{
    url: 'critic_movie.csv'
  }}
  title="Number of critics for each movie"
  xAxis="movie"
  yAxis="rate"
/>

<FlatUiTable
  data={{
    url: 'movies.csv'    
  }}
/>

## Reviews

<FlatUiTable
  data={{
    url: 'all_reviews.csv'    
  }}
/>
