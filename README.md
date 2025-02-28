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

## First Five Rows of the Dataset

| gameId       | blueWins | blueWardsPlaced | blueWardsDestroyed | blueFirstBlood | blueKills | blueDeaths | blueAssists | blueEliteMonsters | blueDragons | ... | redAvgLevel | redTotalExperience | redTotalMinionsKilled | redTotalJungleMinionsKilled | redGoldDiff | redExperienceDiff | redCSPerMin | redGoldPerMin | Cluster | Cluster Name        |
|-------------|----------|----------------|------------------|---------------|----------|-----------|------------|----------------|------------|-----|------------|------------------|-------------------|----------------------|------------|----------------|------------|-------------|---------|------------------|
| 4519157822  | 0        | 28             | 2                | 1             | 9        | 6         | 11         | 0              | 0          | ... | 6.8        | 17047            | 197               | 55                   | -643       | 8              | 19.7       | 1656.7      | 0       | Gameplay Stats     |
| 4523371949  | 0        | 12             | 1                | 0             | 5        | 5         | 5          | 0              | 0          | ... | 6.8        | 17438            | 240               | 52                   | 2908       | 1173           | 24.0       | 1762.0      | 2       | Team Objectives    |
| 4521474530  | 0        | 15             | 0                | 0             | 7        | 11        | 4          | 1              | 1          | ... | 6.8        | 17254            | 203               | 28                   | 1172       | 1033           | 20.3       | 1728.5      | 1       | Economic Indicators|
| 4524384067  | 0        | 43             | 1                | 0             | 4        | 5         | 5          | 1              | 0          | ... | 7.0        | 17961            | 235               | 47                   | 1321       | 7              | 23.5       | 1647.8      | 2       | Team Objectives    |
| 4436033771  | 0        | 75             | 4                | 0             | 6        | 6         | 6          | 0              | 0          | ... | 7.0        | 18313            | 225               | 67                   | 1004       | -230           | 22.5       | 1740.4      | 2       | Team Objectives    |

