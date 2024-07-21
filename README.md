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

<FlatUiTable
  data={{
    url: 'movies.csv'    
  }}
/>
