# High_Diamond_Ranked_10m-clustering
The “League of Legends Diamond Ranked Games (10 min)” dataset comes from high-ranked matches, capturing key gameplay stats within the first 10 minutes. It provides structured, detailed data, making it useful for analyzing esports performance metrics. This dataset helps measure early-game strategies and player decisions in competitive gaming.

## Dataset Columns and Descriptions

| Column Name | Description |
|-------------|-------------|
| `gameId` | Unique identifier for each match |
| `blueWins` | Binary value (1 = Blue team wins, 0 = Red team wins) |
| `blueWardsPlaced` | Number of wards placed by the blue team |
| `blueWardsDestroyed` | Number of wards destroyed by the blue team |
| `blueFirstBlood` | Binary value (1 = Blue team gets first blood, 0 = Red team) |
| `blueKills` | Number of kills by the blue team |
| `blueDeaths` | Number of deaths by the blue team |
| `blueAssists` | Number of assists by the blue team |
| `blueEliteMonsters` | Number of elite monsters slain by the blue team (Dragons/Heralds) |
| `blueDragons` | Number of dragons slain by the blue team |
| `redAvgLevel` | Average level of red team champions |
| `redTotalExperience` | Total experience points accumulated by the red team |
| `redTotalMinionsKilled` | Total minions killed by the red team |
| `redTotalJungleMinionsKilled` | Total jungle minions killed by the red team |
| `redGoldDiff` | Gold difference favoring the red team |
| `redExperienceDiff` | Experience difference favoring the red team |
| `redCSPerMin` | Creep Score (CS) per minute for the red team |
| `redGoldPerMin` | Gold earned per minute for the red team |
| `Cluster` | Assigned cluster number after K-Means clustering |
| `Cluster Name` | Name assigned to each cluster based on gameplay characteristics |

This dataset is used for clustering and analysis of gameplay patterns, economic indicators, and team objectives.

