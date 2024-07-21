---
title: 'The 100 worst movies of all time'
description: 'Insight of the 100 movies that got the worst critics on Rotten Tomatoes'
---

*By [César Heredia](https://x.com/cahered), data journalist*


<PlotlyBarChart
  data={{
    url: 'density_below_2_5k.csv'
  }}
  title="US cities with density below 2.5K"
  xAxis="city_state"
  yAxis="density"
/>

<FlatUiTable
  data={{
    url: 'movies.csv'    
  }}
/>
