# IPL Match Analysis 
## Till 2019

This repository contains Python code to analyze Indian Premier League (IPL) match data using various visualizations. The data used for analysis is sourced from the `matches.csv` file.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Data](#data)
- [Analysis](#analysis)
  - [Number of Matches Played Each Season](#1-number-of-matches-played-each-season)
  - [Matches Won by Each Team](#2-matches-won-by-each-team)
  - [Match Result: Batting First vs. Bowling First](#3-match-result-batting-first-vs-bowling-first)
  - [Matches Won by Batting First vs. Bowling First (Season-wise)](#4-matches-won-by-batting-first-vs-bowling-first-season-wise)
  - [Toss Result Distribution](#5-toss-result-distribution)
  - [Toss Decision Distribution (Season-wise)](#6-toss-decision-distribution-season-wise)
  - [Top Players of IPL](#7-top-players-of-ipl)
  - [IPL Finals Analysis](#8-ipl-finals-analysis)
  - [Fours and Sixes Analysis](#9-fours-and-sixes-analysis)
  - [Wickets Analysis](#10-wickets-analysis)

## Introduction
IPL is one of the most popular and competitive Twenty20 cricket leagues in the world. The dataset provides information on matches played in different IPL seasons, including details like the winner, toss result, player of the match, and more.

## Prerequisites
Before running the code, make sure you have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn

## Data
The dataset is loaded from the `matches.csv` file and stored in a pandas DataFrame. The primary attributes include match details, winner, toss result, and more.

## Analysis
The code contains several visualizations to provide insights into the IPL matches data.

### 1. Number of Matches Played Each Season
This plot displays the number of matches played in each IPL season. The x-axis represents the seasons, while the y-axis represents the count of matches played.

### 2. Matches Won by Each Team
This visualization shows the number of matches won by each team over all seasons. The x-axis represents the team names, and the y-axis represents the count of matches won.

### 3. Match Result: Batting First vs. Bowling First
This pie chart illustrates the match result, whether the team batting first or bowling first, has won the match. The chart displays the percentage distribution of wins for each type.

### 4. Matches Won by Batting First vs. Bowling First (Season-wise)
This plot shows the number of matches won by teams when batting first and bowling first, categorized season-wise. The x-axis represents the seasons, and the y-axis represents the count of matches won.

### 5. Toss Result Distribution
This pie chart presents the distribution of toss results, indicating the percentage of times teams have chosen to bat or bowl first.

### 6. Toss Decision Distribution (Season-wise)
This plot displays the number of matches won by teams based on their toss decisions (bat or bowl first) in different seasons. The x-axis represents the seasons, while the y-axis represents the count of matches won.

### 7. Top Players of IPL
This visualization shows the top players of the match based on the number of times they were awarded the "Player of the Match" title.

### 8. IPL Finals Analysis
This section provides analysis on IPL finals, including the venues, winners, and the number of times each team has won the IPL title.

### 9. Fours and Sixes Analysis
This section analyzes the number of fours and sixes hit by players and teams in different seasons.

### 10. Wickets Analysis
This section provides insights into the wickets taken by bowlers in IPL matches.

Feel free to explore the code and visualize the IPL match data!
