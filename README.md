# Analysis-of-playing-style-of-cricketers
This project uses K-means clustering to group Indian cricket players into clusters based on their runs and wickets taken in the last 4 years. The project includes data preprocessing, scaling, and visualization to ensure accurate and insightful clustering results.

# Indian Cricket Player Clustering

**Introduction**

This project aims to cluster Indian cricket players based on their recent performances using K-means clustering. The dataset includes batting and bowling statistics of Indian players over the last 4 years.

**Methodology**

1. **Data Collection and Preprocessing:**
   - The project utilizes two CSV files, 'batting.csv' and 'bowling.csv', containing player statistics.
   - The data is cleaned, merged, and preprocessed to handle missing values and ensure consistency.
2. **Feature Scaling:**
   - The 'Runs' and 'Wickets' features are scaled using StandardScaler to ensure that both features contribute equally to the clustering process.
3. **K-means Clustering:**
   - The K-means algorithm is applied to the scaled data to group players into clusters based on their runs and wickets.
   - The Elbow Method is used to determine the optimal number of clusters (K).
4. **Visualization:**
   - Scatter plots are used to visualize the clusters and identify player roles (batsmen, bowlers, all-rounders).
   - Cluster centers are highlighted to better understand cluster characteristics.

**Results**

The project successfully clusters Indian cricket players into distinct groups based on their performance patterns. The clusters can be interpreted as follows:

- Cluster 1: Batsmen
- Cluster 2: All-rounders
- Cluster 3: Bowlers

**Usage**

1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the `cricket_clustering.ipynb` notebook in Google Colab.

**Dependencies**

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

**Author**

Ruhani Sharma
