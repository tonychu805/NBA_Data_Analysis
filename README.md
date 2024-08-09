# NBA_Data_Analysis #

## Introduction

This project analyzes the evolution of the NBA through the lens of data analytics, exploring three key areas:

1. **Three-point shot evolution:** Examining the transformation of the game since the introduction of the three-point line in the 1979-1980 season. We analyze how shooting patterns and strategies have changed over time, potentially altering team dynamics and scoring trends.
2. **Redefining player positions:** Challenging traditional position classifications by using statistical analysis to create new, data-driven categories. This approach aims to reflect the modern, more versatile style of play and the emergence of "positionless" basketball.
3. **Characteristics of elite players:** Investigating the factors that contribute to individual player success, with a focus on MVP winners. We aim to identify patterns and develop predictive models for exceptional performance.

## Goal

This project utilizes multiple datasets to analyze the NBA's evolution, focusing on three main areas:

1. **Three-point shot trends:**
  - Analyzes data from 1979 onwards, when the three-point line was introduced.
  - Examines average three-point attempts, field goal percentages, and elite shooter ratios.
  - Investigates correlations between shot distance, field goal percentage, and points per shot.

2. **Player classification:**
  - Unsupervised learning techniques (K-Means and Hierarchical clustering) are used to redefine player positions based on in-game statistics.
  - Aims to create data-driven categories that reflect modern, versatile playing styles.

3. **MVP prediction:**
  - Employs supervised learning models (Support Vector Machine, Decision Tree, and Random Forest) to predict MVP winners.
  - Uses data from 1980-2015 for training and 2016-2022 for testing.
  - Explores the impact of multicollinearity and dimensionality reduction on model performance.

## Data Source

The research leverages various NBA datasets, including in-game performances, shot locations, All-Star selections, and MVP voting. It builds upon the foundation of sports analytics pioneered by figures like Stephen Jay Gould and innovative approaches used by teams such as the Oakland Athletics and Golden State Warriors.
By combining historical context with rigorous data analysis, this project seeks to provide fresh insights into the NBA's evolution, player development, and the changing nature of the game. The findings may be valuable for teams, analysts, and fans looking to deepen their understanding of basketball's past, present, and potential future trends.

- NBA Height and Weight Analysis: https://www.kaggle.com/code/justinas/nba-height-and-weight-analysis/data?select=all_seasons.csv
- NBA Stats (1947 – Present): https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats
- 2020 – June – NBA Shots (1997 – 2019): https://data.world/sportsvizsunday/june-2020-nba-shots-1997-2019

## Results

While sports analytics provide valuable insights and tools for decision-making, intangible factors like passion, leadership, and interpersonal skills remain crucial. Analytics should be used to inform strategies and identify issues, but teams must also understand players on a personal level to balance organizational and player interests effectively.

**1. Three-point shot evolution:**

  - The analysis shows that while three-point attempts have increased, the field goal percentage has plateaued at 34-36%, with decreasing standard deviation.

![image](https://github.com/user-attachments/assets/7c7d36bc-b850-410b-be7e-fd213042d384)
  - This suggests players are improving at three-point shooting but may be approaching a biological limit, similar to Stephen Jay Gould's concept of an "invisible right wall" in sports performance.
  - Three-point shooting has become a legitimate tactic, valued by teams and rewarded in player contracts.


**2. Player position redefinition:**

  - Traditional player positions no longer accurately represent on-court roles.
  - Machine learning techniques (K-Means and Hierarchical clustering) can identify new player categories based on in-game statistics. These new categorizations can help teams in scouting and roster formation.
  - The analysis confirms the importance of having a franchise-level player, surrounded by complementary roles that have evolved over time.


**3. MVP prediction:**

  - The study presents a more objective approach to predicting MVP winners using historical performance data.
  - Combining Principal Component Analysis with Support Vector Machine achieved 95% accuracy in predicting MVPs from 2016 to 2022.

