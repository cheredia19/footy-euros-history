---
title: 'The history of football euros'
author: 'César Heredia, data journalist'
description: 'A detailed look at the seventeen euros held since 1960'
modified: '2024-07-10'
files: ['euros_summary.csv','euro_winners.csv','runner_ups.csv','participations_country.csv']
group: 'Sports'
---

### Summary of all European Championships
<FlatUiTable
  data={{
    url: 'euros_summary.csv'    
  }}
/>

### Winners of European Championships
<PlotlyBarChart
  data={{
    url: 'euro_winners.csv'
  }}
  title="Spain and Germany are the only countries with three Euros each"
  xAxis="winner"
  yAxis="championships"
/>

### Runner-ups of European Championships
<PlotlyBarChart
  data={{
    url: 'runner_ups.csv'
  }}
  title="The USSR is the only country with three runner-up finishes"
  xAxis="runner_up"
  yAxis="number"
/>

### Participations by country in the history of the European Championships
<FlatUiTable
  data={{
    url: 'participations_country.csv'    
  }}
/>

### Rate of matches won by country
<FlatUiTable
  data={{
    url: 'winner_country.csv'    
  }}
/>

### All matches history of the European Championships
<FlatUiTable
  data={{
    url: 'all_matches.csv'    
  }}
/>
