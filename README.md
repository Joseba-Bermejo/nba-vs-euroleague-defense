# 3-Point shooting efficency evolution: NBA vs EuroLeague

### Introduction

Over the past decade, both the NBA and EuroLeague have experienced a significant rise in 3-point attempts. While it’s commonly believed that increased volume might reduce efficiency due to the shot’s difficulty, this project explores whether teams have not only relied more on 3-pointers but also sustained, or even improved, their accuracy. The goal is to challenge traditional assumptions about the trade-off between volume and efficiency in modern basketball.

### Glossary

- 3PA (3-Point Attempts): The average number of 3-point shots a player/team attempts per game.
- 3P% (3-Point Percentage): The success rate of 3-point shots, calculated as the percentage of made 3-pointers out of total attempts.
- FGA (Field Goal Attempts): The total number of shots a player/team attempts per game, including both 2-point and 3-point shots.
- 3PA ratio: The percentage of total field goal attempts that are 3-point shots, calculated as (3PA ÷ FGA) × 100.

### Questions I want to answer

- How has the 3PA ratio evolved YoY in both leagues?
- What are the YoY trends in average 3PA and 3P%?

### Hypothesis

1. The NBA has seen a greater increase in the 3P ratio than the EuroLeague over the past decade.
2. A higher amount of 3PA doesn't lead to lower shooting accuracy in the NBA or EuroLeague.

### Data Sources

Data for this project has been sourced from:
- [NBA Stats API](https://pypi.org/project/nba_api)
- [EuroLeague API](https://pypi.org/project/euroleague-api)

### Methodology

1. Collect 10 years of NBA and EuroLeague team-level 3PA, 3P%, FGA, and 3PA ratio.
2. Clean and standardize datasets
3. Normalize seasons and align date ranges for comparison
4. Analyze trends
5. Visualize correlations, answer the questions and test the hypothesis

### Conclusion

The final analysis will clarify whether the modern shift to long-range shooting has truly compromised shooting efficiency, or if players and teams have simply become better at adapting.

### Other resources

- [Trello (Kanban Board)](https://trello.com/b/N9p2efYk/nba-vs-euroleague-defense)

