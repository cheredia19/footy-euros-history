---
title: 'The history of football euros'
author: 'César Heredia, data journalist'
description: 'A detailed look at the seventeen euros held since 1960'
modified: '2024-07-10'
files: ['euros_summary.csv','euro_winners.csv','runner_ups.csv']
group: 'Sports'
---

### Summary of all Euro competitions
<FlatUiTable
  data={{
    url: 'euros_summary.csv'    
  }}
/>

### Winners of Euro competitions
<PlotlyBarChart
  data={{
    url: 'euro_winners.csv'
  }}
  title="Spain and Germany are the only countries with three Euros each"
  xAxis="winner"
  yAxis="championships"
/>

### Runner-ups of Euro competitions
<PlotlyBarChart
  data={{
    url: 'runner_ups.csv'
  }}
  title="The USSR is the only country with three runner-up finishes"
  xAxis="runner_up"
  yAxis="number"
/>
