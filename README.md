# TikTok Influencer Clustering (2025)

This project applies **DBSCAN clustering** to identify patterns among the **Top 100 TikTok influencers in 2025**, based on their **Followers, Likes, and Uploads**. The dataset is processed, clustered, and visualized to provide insights into different influencer categories.

## Features
- **DBSCAN Clustering**: Automatic grouping of influencers without predefined categories.
- **Silhouette Score Optimization**: Grid search to find the best `eps` and `min_samples` values.
- **Data Normalization**: StandardScaler ensures features have equal weight.
- **Cluster Labeling**: Meaningful names replace numeric cluster IDs.
- **Visualization**: Log-scale scatter plot for better cluster representation.

## Installation
Clone the repository and install the required libraries:
```bash
git clone https://github.com/yourusername/tiktok-influencer-clustering.git
cd tiktok-influencer-clustering
pip install -r requirements.txt
```

## Usage
1. **Prepare the dataset**: Place `Top_100_tiktokers_in_2025.csv` in the project folder.
2. **Run the script**:
    ```bash
    python clustering.py
    ```
3. **View results**: The updated dataset `Updated_Top_100_TikTok_Influencers_2025.csv` will be generated.

## Sample Data (First 5 Rows)

| gameId       | blueWins | blueWardsPlaced | blueWardsDestroyed | blueFirstBlood | blueKills | blueDeaths | blueAssists | blueEliteMonsters | blueDragons | ... | redAvgLevel | redTotalExperience | redTotalMinionsKilled | redTotalJungleMinionsKilled | redGoldDiff | redExperienceDiff | redCSPerMin | redGoldPerMin | Cluster | Cluster Name        |
|-------------|----------|----------------|------------------|---------------|----------|-----------|------------|----------------|------------|-----|------------|------------------|-------------------|----------------------|------------|----------------|------------|-------------|---------|------------------|
| 4519157822  | 0        | 28             | 2                | 1             | 9        | 6         | 11         | 0              | 0          | ... | 6.8        | 17047            | 197               | 55                   | -643       | 8              | 19.7       | 1656.7      | 0       | Gameplay Stats     |
| 4523371949  | 0        | 12             | 1                | 0             | 5        | 5         | 5          | 0              | 0          | ... | 6.8        | 17438            | 240               | 52                   | 2908       | 1173           | 24.0       | 1762.0      | 2       | Team Objectives    |
| 4521474530  | 0        | 15             | 0                | 0             | 7        | 11        | 4          | 1              | 1          | ... | 6.8        | 17254            | 203               | 28                   | 1172       | 1033           | 20.3       | 1728.5      | 1       | Economic Indicators|
| 4524384067  | 0        | 43             | 1                | 0             | 4        | 5         | 5          | 1              | 0          | ... | 7.0        | 17961            | 235               | 47                   | 1321       | 7              | 23.5       | 1647.8      | 2       | Team Objectives    |
| 4436033771  | 0        | 75             | 4                | 0             | 6        | 6         | 6          | 0              | 0          | ... | 7.0        | 18313            | 225               | 67                   | 1004       | -230           | 22.5       | 1740.4      | 2       | Team Objectives    |

## Output
- Clustered dataset with meaningful labels.
- Identified **outliers** (influencers with extreme popularity).
- Visualized influencer clusters.

## Contributing
Feel free to submit pull requests or raise issues for improvements.

## License
MIT License




