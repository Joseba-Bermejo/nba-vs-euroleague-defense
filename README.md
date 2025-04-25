# 3-Point shooting efficency evolution: NBA vs EuroLeague

### Introduction

Over the past decade, both the NBA and EuroLeague have experienced a significant rise in 3-point attempts. While it’s commonly believed that increased volume might reduce efficiency due to the shot’s difficulty, this project explores whether teams have not only relied more on 3-pointers but also sustained, or even improved, their accuracy. The goal is to challenge traditional assumptions about the trade-off between volume and efficiency in modern basketball.

### Glossary

- 3PA (3-Point Attempts): The average number of 3-point shots a player/team attempts per game.
- 3PM (3-Point Made): The average number of 3-point shots a player/team makes per game.
- 3P% (3-Point Percentage): The success rate of 3-point shots, calculated as the percentage of made 3-pointers out of total attempts.
- 2PA (2-Point Attempts): The average number of 2-point shots a player/team attempts per game.
- 2PM (2-Point Made): The average number of 3-point shots a player/team makes per game.
- 2P% (2-Point Percentage): The success rate of 2-point shots, calculated as the percentage of made 2-pointers out of total attempts.
- FGA (Field Goal Attempts): The total number of shots a player/team attempts per game, including both 2-point and 3-point shots.
- FG% (Field Goal Percentage): The overall shooting efficiency, calculated as the percentage of all field goals made (2PM + 3PM) out of total field goal attempts (2PA + 3PA).
- 3PA ratio: The percentage of total field goal attempts that are 3-point shots, calculated as (3PA ÷ FGA) × 100.
- av_att (Average Attendance per game): The average number of spectators attending a team’s games, calculated across all home games in a season.


#### Key metrics for my analysis

- 3PA, 3P%, 3PA ratio, FG%, av_att. 


### Questions I want to answer

- What's the trend of 3PA per season in the last 10 years?
- How has the 3PA ratio evolved YoY?
- Assuming an increase in 3PA ratio, how does that impact 3P% and shooting efficiency overall (FG%)?
- Is fan attendance correlated to shooting efficiency (FG% % 3P%)?

### Hypothesis

1. The NBA has seen a greater increase in the 3P ratio than the EuroLeague over the past decade.
2. A higher amount of 3PA doesn't correlate to lower 3P% or lower shooting efficiency in the NBA or EuroLeague.
3. Lower fan attendance correlates with higher 3P% in both leagues. 

### Data Sources

Data for this project has been sourced from:
- [NBA Stats API](https://pypi.org/project/nba_api)
- [EuroLeague API](https://pypi.org/project/euroleague-api)

### Methodology

1. Collect 10 years of NBA and EuroLeague team-level metrics mentioned in the glossary.
2. Data Wrangling: standardize datasets, create new metrics (e.g. 3PA ratio, FG% in the case of the Euroleague, etc.), drop unnecesary columns.
3. Normalize seasons and align date ranges for comparison
4. Analyze trends and create compelling visualizations
5. Observe correlations, answer the questions and test the hypothesis

### Conclusion

The final analysis challenges the assumption that increased 3-point volume comes at the cost of efficiency. Instead, it suggests that both leagues (particularly the NBA) have adapted to the modern game by improving accuracy alongside volume. External factors like fan attendance may also influence shooting accuracy, potentially playing a role in player performance.

### Other resources

- [Trello (Kanban Board)](https://trello.com/b/N9p2efYk/nba-vs-euroleague-defense)

