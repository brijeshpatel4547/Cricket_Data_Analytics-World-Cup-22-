# Cricket_Data_Analytics-World-Cup-22
Analyzing the T20 Cricket World Cup 2022 data to find the data insights and select the best 11 of world cup.

Python - For data Transformation
Power BI - For visualization Dashboards

Categories of the data:
1. batting_Summary.csv -> Includes the data about the batting information per match
2. bowling_summary.csv -> Includes the data about the bowling information per match
3. player_summary.csv -> Includes the data about each player taken part in the world cup
4. match_summary.csv -> Inclues the match details about teams played, who won the match and match-id etc..

Five categories of players are shortlisted based on the parameters:
1. **Openers** : Batting Average > 30 ; Total Runs > 100 ; Batting Position < 4; Boundary % > 50 %; Strike Rate > 140
2. **Anchors/Middle Orders** : Batting Average > 40 ; Batting Position > 2 ; Strike Rate > 125 ; Avg Balls Faced > 20 ; Innings Batted > 3
4. **Finishers**: Batting Average > 20 ; Batting Position > 4 ; Strike Rate > 140 ; Avg Balls Faced > 12 ; Innings Batted > 3
5. **All-Rounders** : Batting Average > 15 ; Batting Position > 4 ; Strike Rate > 140 ; Innings Batted >= 3; Innings Bowled >= 3 ; Economy < 7 ; Bowling S/R < 20
6. **Fast Bowlers** : Economy <= 7 ;  Bowling S/R < 16 ; Bowling Style = '%Fast%' ; Innings Bowled > 4
