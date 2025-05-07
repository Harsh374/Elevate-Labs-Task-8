# K-means Clustering for Customer Segmentation

## Overview
This repository contains implementation of K-means clustering algorithm for customer segmentation using the Mall Customer Segmentation Dataset. The project demonstrates unsupervised learning techniques to identify distinct customer groups based on spending patterns and income.

## Dataset
The analysis uses the Mall Customer Segmentation Dataset which includes:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Key Features
- Data preprocessing and visualization
- K-means clustering implementation
- Optimal cluster determination using Elbow Method
- Cluster evaluation with Silhouette Score
- PCA for dimensionality reduction and visualization
- Detailed cluster analysis and interpretation

## Requirements
```
pandas
numpy
matplotlib
scikit-learn
seaborn
```

## Usage
1. Clone the repository
```bash
git clone https://github.com/Harsh374/Elevate-Labs-Task-8.git
cd Elevate-Labs-Task-8
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the clustering script
```bash
python kmeans_clustering.py
```

## Results
The analysis identifies optimal customer segments based on Annual Income and Spending Score. The implementation:
- Determines the optimal number of clusters (K=5) using the Elbow Method
- Evaluates cluster quality using Silhouette Score
- Visualizes clusters with color-coding
- Provides insights into customer behavior patterns

## Visualizations
- Elbow Method curve for determining optimal K
- Silhouette Score analysis
- 2D cluster visualization with centroids
- PCA visualization for higher-dimensional analysis
- Feature relationship plots

## Potential Applications
- Targeted marketing strategies
- Personalized customer experiences
- Inventory planning based on customer segments
- Promotional campaign optimization

## Contact
For questions or feedback, please reach out to harshnandu03@gmail.com

## License
This project is licensed under the MIT License - see the LICENSE file for details.
