---
title: 'The history of football euros'
author: 'César Heredia, data journalist'
description: 'A detailed look at the seventeen euros held since 1960'
modified: '2024-07-10'
files: ['euro_countries.csv','euros_summary.csv','countries_euros.csv','euro_winners.csv','matches.csv','runner_ups.csv','win_rate_country.csv']
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

### Winning rates of countries in European Championships*
<FlatUiTable
  data={{
    url: 'win_rate_country.csv'    
  }}
/>
*NOTE: Only wins in regular time are taken into consideration. Wins in aggregated extra time, golden or silver goal, or by penalties are counted as DRAWS*

### Participations by country in the history of the European Championships
<FlatUiTable
  data={{
    url: 'countries_euros.csv'    
  }}
/>

### All matches of the European Championships
<FlatUiTable
  data={{
    url: 'matches.csv'    
  }}
/>
