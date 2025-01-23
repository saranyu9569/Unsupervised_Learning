# Unsupervised Learning Techniques

This project demonstrates various unsupervised learning methods, focusing on clustering algorithms such as K-Means, DBSCAN, and Hierarchical Clustering. The notebook explores their functionality and visualizes the results on sample data.

## Features of the Project

- **K-Means Clustering**:
  - Implements K-Means to partition data into clusters.
  - Visualizes the clusters for better understanding.

- **DBSCAN (Density-Based Spatial Clustering)**:
  - Groups data points based on density.
  - Identifies noise and outliers effectively.

- **Hierarchical Clustering**:
  - Constructs a dendrogram to illustrate data clustering hierarchy.
  - Performs agglomerative clustering for group formation.

- **Data Visualization**:
  - Uses Matplotlib to display clustering results.

## Requirements

To run this project, ensure you have the following Python libraries installed:

- `numpy`
- `matplotlib`
- `scikit-learn`
- `scipy`

Install the dependencies using pip:

```bash
pip install numpy matplotlib scikit-learn scipy
```

## Usage

1. Clone this repository and navigate to the project directory:

```bash
git clone <repository-url>
cd <repository-directory>
```

2. Open the Jupyter Notebook `Unsupervised.ipynb`.

3. Follow the steps in the notebook to:
   - Generate synthetic datasets.
   - Apply clustering algorithms (K-Means, DBSCAN, Hierarchical Clustering).
   - Visualize the results.

## Example Output

### K-Means Clustering
Visualizes clusters with distinct centroids.

### DBSCAN
Identifies clusters along with noise points.

### Hierarchical Clustering
Displays a dendrogram and clustered groups.

## Notes

- Adjust hyperparameters like the number of clusters for K-Means or `eps` and `min_samples` for DBSCAN to suit different datasets.
- The notebook uses synthetic datasets but can be adapted for real-world data.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- `scikit-learn` for clustering algorithms.
- `matplotlib` for visualization tools.
- `scipy` for hierarchical clustering utilities.

Feel free to contribute or raise issues if you encounter any problems!
