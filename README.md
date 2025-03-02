# League of Legends Match Data Clustering (2025)

This project applies **K-Means Clustering** to analyze and categorize high-ranked League of Legends matches based on gameplay statistics, economic indicators, and team objectives.

## Features
- **K-Means Clustering**: Determines optimal grouping of matches using gameplay data.
- **Elbow Method**: Identifies the best number of clusters.
- **Data Normalization**: StandardScaler ensures fair weight distribution among features.
- **PCA for Visualization**: Reduces dimensions for easy cluster representation.
- **Cluster Analysis**: Examines win rates, feature contributions, and centroids.

## Installation
Clone the repository and install the required libraries:
```bash
git clone https://github.com/yourusername/lol-match-clustering.git
cd lol-match-clustering
pip install -r requirements.txt
```

## Usage
1. **Load the dataset**: Ensure `high_diamond_ranked_10min.csv` is in your Google Drive.
2. **Run the script**:
    ```python
    python clustering.py
    ```
3. **View results**: The processed dataset `high_diamond_ranked_10min_clustered.csv` will be generated.

## Sample Data (First 5 Rows)
```
blueKills  blueDeaths  blueAssists  redKills  redDeaths  redAssists  blueTotalGold  redTotalGold  blueGoldDiff  redGoldDiff  blueDragons  blueHeralds  redDragons  redHeralds  Cluster  Cluster Name
5          3           7            3        5          4           12000          11500         500           -500         1            0            1           0            0        Gameplay Stats
6          2           10           2        6          5           13500          12800         700           -700         2            1            0           0            1        Economic Indicators
3          4           5            4        3          6           11000          11150         -150          150          0            1            1           0            2        Team Objectives
```

## Output
- Clustered dataset with meaningful labels.
- PCA visualization of clusters.
- Identification of dominant features contributing to each cluster.
- Win rate analysis per cluster.

## Contributing
Feel free to submit pull requests or raise issues for improvements.

## License
MIT License

