# Game Data Analysis Project

## Project Overview

This repository contains the analysis and findings from a game data analysis project completed. The project explores various aspects of game data, aiming to extract valuable insights for game development and player engagement strategies. By combining SQL queries and data visualization techniques, this project attempts to address a variety of questions that would be valuable for understanding player behavior, game monetization, and overall game health.

## Project Goals

The core objectives of this project were to:
* Analyze game data to derive actionable insights.
* Practice SQL querying for data extraction and manipulation.
* Apply data visualization to communicate findings effectively.
* Connect theoretical knowledge with practical game data scenarios.

## Key Questions Addressed

This project tackles a number of key questions about the game data, encompassing:

1.  **Break-Even Point:** What is the maximum Cost Per Install (CPI) allowed for a break-even point?

    *   *Approach*: Analyzed daily revenue, calculated net revenue, and formulated a model based on ad impressions and CPM to arrive at maximum CPI. Additionally, market costs were incorporated to provide a more realistic metric.

2. **Daily Average Revenue Per Daily Active User (ARPDAU):** What is the daily ARPDAU?

    *   *Approach*: Calculated ARPDAU for each day and examined the relationship between DAU and ARPDAU.
  
3. **50 Day Break-Even ARPDAU:** What should the average daily ARPDAU be to reach break-even in 50 days?

     *  *Approach*: Approached the challenge first with a retention model, but moved to a simple calculation by using total players in a 50-day period and a calculation based on initial cost to reach the breakeven goal.

4. **Daily Active Users (DAU):** Using the available tables, how can daily active users be determined?

    *  *Approach*: Used the `users_daily` table, extracted event dates, and counted distinct users.

5.  **Daily Conversion Rate:** What are the daily conversion rates for players in the game?

    *  *Approach*: Calculated conversion rates daily to observe daily fluctuations in user conversions.
      
6. **Most Difficult Stage:** Which stage in the game is the most challenging for players?

    *   *Approach*: Computed the win rate and non-finisher rates by stage and identified the stage with the lowest win rate as the most difficult.

7. **Game Time:** How is player engagement with the game affected by the average and median time they are playing?

    * *Approach*: Calculated and compared the average and median time spent in the game by player.
 
8. **Gem Acquisition:** Based on the available data, which in-game sources provide the best opportunities for gem acquisition?

     * *Approach*: Calculated the number of gems gained from various sources and highlighted the best sources for the players and the game.

9. **Stage Completion Attempts:** How many attempts, on average and median, do players need to complete each stage?

     * *Approach*: Determined average and median attempts to finish stages for each of the stages in the game.

10. **Cheat/Fraud Prevention:** What actions should a game data analyst take to prevent cheating and fraud?

     * *Approach*: Used standard deviations to find outliers, while proposing actions like setting limitations with developers, removing cheaters, and creating different segments to monitor.

11.  **Custom Analysis:** Develop a custom analysis table to study the relationship between level-up speed, spending, and player retention.
    * Approach: Combined win/lose ratios, game time, spending, and retention status in a single table for further analysis.

## Analysis Approaches

The following approaches were used throughout the analysis process:

*   **SQL Querying:** Raw data was extracted, filtered, and aggregated using SQL.
*   **Data Visualization:** Charts and graphs were created to reveal data patterns.
*   **Cohort Analysis:** Analyzed specific groups of users (when applicable).
*   **Statistical Calculations:**  Computed daily averages, percentages, standard deviations, etc.
*   **Data Interpretation:** Drew inferences from the data insights and provided relevant commentary.

## Author

This project was completed by **Muhammet Uzun**.
