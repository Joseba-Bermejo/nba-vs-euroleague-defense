# 3-Point shooting efficency evolution: NBA vs EuroLeague

### Introduction

Over the past decade, both the NBA and EuroLeague have experienced a significant rise in 3-point attempts. While it’s commonly believed that increased volume might reduce efficiency due to the shot’s difficulty, this project explores whether teams have not only relied more on 3-pointers but also sustained, or even improved, their accuracy. The goal is to challenge traditional assumptions about the trade-off between volume and efficiency in modern basketball.

### Questions I want to answer

- What are the YoY trends in average 3PA and 3P%?
- How has the proportion of 3-point attempts (3PA) relative to total field goal attempts (FGA) evolved YoY in both leagues?
- What is the correlation between increased volume and accuracy?
- How has 3-point shooting evolved league-wide in the NBA and EuroLeague over the last decade?

### Hypothesis

1. Despite the rise in average 3-point attempts per game over the past decade, 3-point shooting accuracy in both the NBA and EuroLeague has remained stable, or even improved, year over year.
2. The NBA has seen a greater increase in the share of 3-point attempts relative to total shots than the EuroLeague over the past decade.

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

