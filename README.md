# NFL-Fantasy-Football-Rankings
For this project, I will be performing clustering techniques on NFL players by position: Quarterback, Runningback, and Wide Receiver. The 2020 NFL season is fast approaching, and for fantasy football enthusiasts, deciding who to place on your team is of the upmost importance.

With this analysis, I will be using the 2019 NFL statistics downloaded from FantasyPros to cluster each NFL player into "tiers" based on their 2019 performance. In this manner, I can determine which players are best to choose for my own team. I also modified the dataset by including two very important statistics: 'Games Played' and 'Fantasy Points Scored per Game'. These two stats were not included in the original dataset, so I took it upon myself to include them.

There are several assumptions I will be working with for each dataset. For one, I will only work with players who played in 2019 because I'd like to cluster players who have already played an NFL game. This does exclude incoming rookies and untested new starters, but since those players are untested and they have no real impact so far, it would be unfair to include them among the players who have demonstrated their play-making ability in the NFL.

Secondly, there are also players who have played in 2019 who are no longer on a team (known in the data as a free agent (FA)). If you are a player without a team, it is impossible to have any fantasy football impact. Thus, at the time of conducting this analysis, if any player is not on team, no matter well they performed in 2019, I will have to drop them from the dataset.

With that said, I will be arbitrarily starting with quarterbacks, then moving on to runningbacks, and then concluding with an analysis of wide receivers.
