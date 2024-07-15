---
title: 'UEFA European Championships in figures'
description: 'A detailed data look at the seventeen football European championships held since 1960'
---

*By [César Heredia](https://x.com/cahered), data journalist*

The victory of Spain over England by 2-1 closed another fascinating chapter of the UEFA European Competitions. It represents the fourth championship for the Spaniards, overtaking Germany as the most winning team in the Euro's history. France and Italy complete the list of countries with more than one European championship, while other six nations have won it once each.

### The kings of Europe
<PlotlyBarChart
  data={{
    url: 'winners.csv'
  }}
  title="Spain surpassed Germany as the most winning country"
  xAxis="winner"
  yAxis="championships"
/>

England reached Italy, and former Yugoslavia in second place among the countries with the most runner-up finishes. The former USSR and Germany lead that figure, with three.

### Two in a row
<PlotlyBarChart
  data={{
    url: 'runnerups.csv'
  }}
  title="Two runner-up finishes for England in 2020 and 2024 put them in second place"
  xAxis="runner_up"
  yAxis="number"
/>

Spain is the only country with over 50 games played in the competition's history (52). The closest followers are France and Italy. Also, Spain has won the most games (25), followed by the Netherlands (22), and Italy (21).

West Germany played until Euro 1988 when they hosted the competition. Since the [German reunification](https://www.britannica.com/place/Germany/The-reunification-of-Germany), they began playing as Germany in Sweden (1992).

As a single nation, Germany has participated uninterruptedly since 1972 (Belgium). Germans won 28 of 58 games played (a winning rate of 48.3%).

### Winning rates of countries in European Championships*
<FlatUiTable
  data={{
    url: 'rate_win_country.csv'    
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

<FlatUiTable
  data={{
    url: 'countries_euro.csv'
  }}
/>

## A glimpse of the seventeen UEFA Euro competitions

The first UEFA Euro Championship was held for the first time in France, from June 7 to June 10, 1960. There were only four teams (Czechoslovakia, France, Yugoslavia, and the USSR). Four matches were played: two semifinals, the game for the third place, and the final. The USSR defeated Yugoslavia in aggregated extra time by 2-1, making them the first-ever European champions.

The four-team format continued until 1976 when Euro was held in the extint Yugoslavia. Czechoslovakia won their first and only Euro, defeating West Germany on penalties with a [game-winning penalty from Antonin Panenka](https://youtu.be/ROG4-QPIDgo?feature=shared&t=101) that made history by creating a new style of kicking from the spot, imitated by the likes of Francesco Totti, Zinedine Zidane, and Andrea Pirlo, among others.

Euro 1980 brought **the first expansion of participating teams by increasing the number to eight**. Also, Italy 1980 was the last time that a match for third place was played. Czechoslovakia became the last official third place in European competitions by beating the hosts on penalties. West Germany defeated Belgium by 2-1 in front of 47,860 spectators at the Stadio Olimpico in Rome. It was the second title for the Germans.

From France 1984 to Sweden 1992, there were three new champions: France, the Netherlands, and Denmark. **Platini's France was the last host to win a European competition**. Four years later, the Netherlands, led by legendary Rinus Michels, beat the USSR 2-0, winning the only major tournament in its history, while Denmark, despite not originally qualifying (it entered because [Yugoslavia was banned from the competition due to the attacks on Bosnia and Herzegovina](https://www.upi.com/Archives/1992/05/31/Yugoslavia-barred-from-European-Championships/3160707284800/)), defeated Germany 2-0, winning its greatest soccer achievement to date.

The second team expansion happened in Euro 1996. England hosted one of the most memorable competitions with 16 teams battling in 31 games. But, unfortunately for the English, the cup "did not come home". As striker Gary Lineker once famously said, football is a sport where **22 men chase a ball for 90 minutes, and in the end, the Germans always win.** That was exactly what happened 28 years ago when Gareth Southgate, the current England tactician, [failed from the spot against Germany in the semifinals](https://www.telegraph.co.uk/news/2021/07/11/dont-cry-england-inside-story-gareth-southgate-felt-euro-96/). Eventually, the Germans defeated the Czech Republic by 2-1 at the old Wembley stadium with a Golden Goal from Oliver Bierhoff, the first of its kind in the history of the European Championships.

A definition by a Golden Goal occurred again in the final of Euro 2000, hosted by Belgium and the Netherlands. That time was David Trezeguet with a magic volley that defeated goalkeeper Francesco Toldo and Italy by 2-1, sinking the dreams of the *azzurri*.

Portugal 2004 was wild. The hosts, packed with a loaded team that included Rui Costa, Luis Figo, Nuno Gomes, Ricardo Carvalho, and a debutant called Cristiano Ronaldo, was one of the favorites. But a German tactician called Otto Rehhagel and his team Greece defied the odds and defeated Portugal twice, in the Group Phase, and in the final.

Euro 2008 marked the second time that two countries (Austria and Switzerland) cohosted the competition. Spain, with the FC Barcelona-branded *tiki-taka* and directed by Luis Aragonés, defeated Germany by 1-0 with a goal from Fernando *'el niño'* Torres to seal the second Euro championship for the Spaniards.

Spain cemented the domination of European (and world) football in Euro 2012, held in Poland and Ukraine. That time, under Vicente Del Bosque, crushed Cesare Prandelli's Italy by 4-0 in Kiev, earning their third continental title and second in a row.

**The number of teams were expanded to 24 in the UEFA Euro 2016**. As a consequence, a Round of 16 stage was played in the tournament for the first time. For context, 24 teams disputed the Football World Cup from 1982 to 1994. 51 games were played. Portugal defeated the hosts France by 1-0 with a goal in aggregated extra time to reach their first and only European championship.

Euro 2020 was a special tournament for many reasons: it developed in the middle of a pandemic, had multiple venues in 11 European countries, and was held in the summer of 2021 due to the restrictions related to COVID-19. Italy reached its second championship by defeating England in Wembley in a tense penalty shootout.

Below is a summary of the seventeen European competitions to date:

<FlatUiTable
  data={{
    url: 'euros_summary.csv'    
  }}
/>

Nine hundred and thirty-six goals have been converted in 388 games in the European competitions, a media of 2.4 goals per match. The most prolific game occurred in 1964 when France and Yugoslavia entertained the 26,370 attendees with nine goals. There have been 77 draws in the history of Euros, in thirty-six times of those matches there were no annotations.

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

Forty-eight red cards have been delivered by referees during the competitions. Belgium-Netherlands 2000 and England 1996 are the competitions where most players were penalized with eight and seven, respectively. Five tournaments didn't register any red cards, the last time that happened was in Sweden 1992, according to the data.

### All matches of the European Championships
<FlatUiTable
  data={{
    url: 'matches.csv'    
  }}
/>

## Curiosities

### Home/away ratio in European Championships matches
<FlatUiTable
  data={{
    url: 'home_away_ratio.csv'    
  }}
/>

### Matches regular/drawn/golden/silver/penalties

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
