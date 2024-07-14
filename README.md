---
title: 'UEFA European Championships in figures'
author: 'César Heredia, data journalist'
description: 'A detailed data look at the seventeen football European championships held since 1960'
modified: '2024-07-14'
files: ['euro_countries.csv','euros_summary.csv','countries_euros.csv','euro_winners.csv','matches.csv','runner_ups.csv','win_rate_country.csv']
group: 'Sports'
---

The victory of Spain over England by 2-1 closes another fascinating chapter of the UEFA European Competitions. It represents the fourth championship for the Spaniards, overtaking Germany as the most winning team in the Euro's history. France and Italy complete the list of countries with more than one European championship, while other seven nations have won it once each.

### Winners of European Championships
<PlotlyBarChart
  data={{
    url: 'euro_winners.csv'
  }}
  title="Spain and Germany are the only countries with three Euros each"
  xAxis="winner"
  yAxis="championships"
/>

England reached Italy, Germany, and former Yugoslavia in second place among the countries with the most runner-up finishes. The former USSR leads that figure, with three.

### Runner-ups of European Championships
<PlotlyBarChart
  data={{
    url: 'runner_ups.csv'
  }}
  title="The USSR is the only country with three runner-up finishes"
  xAxis="runner_up"
  yAxis="number"
/>

Spain is the only country with over 50 games played in the competition's history (52). The closest followers are France and Italy. Also, Spain has won the most games (25), followed by the Netherlands (22), and Italy (21).

West Germany played until Euro 1988 when they hosted the competition. Since the [German reunification](https://www.britannica.com/place/Germany/The-reunification-of-Germany), they began playing as Germany in Sweden (1992).

As a single nation, Germany has participated uninterruptedly since 1972 (Belgium). Germans won 28 of 58 games played (a winning rate of 48.3%).

### Winning rates of countries in European Championships*
<FlatUiTable
  data={{
    url: 'win_rate_country.csv'    
  }}
/>
*NOTE: Only wins in regular time are taken into consideration. Wins in aggregated extra time, golden or silver goal, or by penalties are counted as DRAWS*

Germany has proved to be one of the most consistent countries in world football, and Europe is a privileged witness to this. The Western European nation said "present" in 14 of the 17 tournaments, followed by Spain (12), France, England, Italy, and the Netherlands, with 12 each.

### Number of participations by country in European Championships
<PlotlyBarChart
  data={{
    url: 'total_part_country.csv'
  }}
  title="Germany has participated in more UEFA European competitions than anyone"
  xAxis="country"
  yAxis="participations"
/>

But how has been the performance of the teams on a tournament-by-tournament basis?

In the following table, you can check the participation and the performance **of each country** in European competitions, from France 1960, to Germany 2024. You can filter by position in any edition of the UEFA Euro tournaments.

### Peformance by country in all European Competitions
<FlatUiTable
  data={{
    url: 'countries_euros.csv'    
  }}
/>

## A glimpse of the seventeen UEFA Euro competitions

The first UEFA Euro Championship was held for the first time in France, from June 7 to June 10, 1960. There were only four teams (Czechoslovakia, France, Yugoslavia, and the USSR). Four matches were played: two semifinals, the game for the third place, and the final. The USSR defeated Yugoslavia in aggregated extra time by 2-1, making them the first-ever European champions.

The semifinal-third place match-final format continued until 1976 when Euro was held in the extint Yugoslavia. Czechoslovakia won their first and only Euro, defeating West Germany on penalties with a [game-winning penalty from Antonin Panenka](https://youtu.be/ROG4-QPIDgo?feature=shared&t=101) that made history by creating a new style of kicking penalties, imitated by the likes of Francesco Totti, Zinedine Zidane, and Andrea Pirlo, among others.

### Summary of all European Championships
<FlatUiTable
  data={{
    url: 'euros_summary.csv'    
  }}
/>

### All matches of the European Championships
<FlatUiTable
  data={{
    url: 'matches.csv'    
  }}
/>

### Goals scored by match in European Championships
<PlotlyLineChart
  data={{
    url: 'goals_by_match.csv'
  }}
  title="France vs. Yugoslavia, held in 1960, is the match with the most goals scored*"
  xAxis="match"
  yAxis="goals_scored"
/>
*NOTE: In regular time*

## Curiosities

### Home/away ratio in European Championships matches
<FlatUiTable
  data={{
    url: 'home_away_ratio.csv'    
  }}
/>

### Home team winning ratio

### Away team winning ratio

### Historic table updated

### Vega chart*

### Attendance by match since Euro 1960
<PlotlyBarChart
  data={{
    url: 'matches_attendance.csv'
  }}
  title="Spain vs. the USSR, held in 1964, got the highest attendance ever"
  xAxis="match"
  yAxis="attendance"
/>

### Attendance by rate (check 1992)
