# League-of-Legends-Exploratory-Data-Analysis
An exploratory data analysis of the top ranked league of legends games.
## Dataset

> League of Legends is a popular moba game allowing people to partake in ranked games against other players where their performance is measured and the better you are (the more you win) the higher you can climb the ranked ladder. High Elo consists of the top 3 ranks in the game; Master, Grand Master, and Challenger. Less than 1% of the entire player base reach these ranks (https://www.esportstales.com/league-of-legends/rank-distribution-percentage-of-players-by-tier). During the game you either play as part of the red side or the blue side. The side you're on affects your in-game view. 

> This dataset consists of three CSV files each formatted identically. Each file represents one High Elo rank. There is one file for Master games, one for Grand Master games, and one for Challenger games. 

The Master_Ranked_Games file consists of 107125 rows and 50 columns. 
The GrandMaster_Ranked_Games file consists of 65896 rows and 50 columns.
The Challenger_Ranked_Games file consists of 26904 rows and 50 columns.

Each row containts the data for one game and includes:

- gameId	
- gameDuraton	
- blueWins	
- blueFirstBlood	
- blueFirstTower	
- blueFirstBaron	
- blueFirstDragon	
- blueFirstInhibitor	
- blueDragonKills	
- blueBaronKills
- blueTowerKills
- blueInhibitorKills
- blueWardPlaced 
- blueWardkills 
- blueKills 
- blueDeath 
- blueAssist 
- blueChampionDamageDealt 
- blueTotalGold
- blueTotalMinionKills 
- blueTotalLevel 
- blueAvgLevel 
- blueJungleMinionKills 
- blueKillingSpree 
- blueTotalHeal 
- blueObjectDamageDealt 
- redWins 
- redFirstBlood 
- redFirstTower
- redFirstBaron 
- redFirstDragon 
- redFirstInhibitor 
- redDragonKills 
- redBaronKills 
- redTowerKills 
- redInhibitorKills
- redWardPlaced 
- redWardkills 
- redKills 
- redDeath
- redAssist	
- redChampionDamageDealt	
- redTotalGold	
- redTotalMinionKills	
- redTotalLevel	
- redAvgLevel	
- redJungleMinionKills	
- redKillingSpree	
- redTotalHeal	
- redObjectDamageDealt

I downloaded this dataset from Kaggle: https://www.kaggle.com/datasets/gyejr95/league-of-legends-challenger-ranked-games2020


## Summary of Findings

> Vision (placing wards) is considerably important if a team wants to win. All members of the team must participate in order to reach higher levels of wards placed. Smaller mistakes/numbers matter more the higher ranked you are and your aim should be to allow yourself to scale in order to make steady progress and win over the course of the game. Regardless of rank, neither first blood nor first tower are indicative that the game is lost and players should work hard to maintain a balanced and positive mental outlook in the face of these experiences. The focus should instead be on pushing for the first inhibitor and the destruction of towers, as these are the highest indicators of a won game. 
