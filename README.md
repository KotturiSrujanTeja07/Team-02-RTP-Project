# Customer Segmentation with KMeans Clustering

This project performs customer segmentation on the "Mall Customers" dataset using KMeans clustering. The goal is to group customers based on characteristics such as age, annual income, and spending score to uncover distinct groups that can help with targeted marketing strategies.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project applies exploratory data analysis and clustering algorithms to segment mall customers based on demographic and behavioral data. Key analysis steps include:
- Exploratory data analysis (EDA) with visualizations for age, income, and spending scores.
- Clustering with KMeans, using metrics like Within-Cluster Sum of Squares (WCSS) and silhouette scores to determine the optimal number of clusters.
- Visualizing clusters and centroids, and saving clustering results for further analysis.

## Dataset
The dataset used here is `Mall_Customers.csv`, which includes:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income**: Annual income in thousands.
- **Spending Score**: Score assigned by the mall based on customer behavior and spending.

## Setup
### Prerequisites
- Python 3.x
- [Jupyter Notebook](https://jupyter.org/) or any Python IDE
- Required packages (install via pip):
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Load the Dataset**: Open `rtp_project.ipynb` in Jupyter Notebook or your IDE, and ensure `Mall_Customers.csv` is in the same directory.
2. **Run Analysis**: Execute cells step-by-step to run EDA, clustering, and visualization.
3. **Visualize Results**: Review the clustering visualizations and silhouette scores to interpret segmentation.

### Key Scripts
- **`rtp_project.ipynb`**: Main script for data analysis, visualization, and clustering.
- **`Mall_Customers.csv`**: Dataset used for clustering.
- **`kmeans_silhouette_scores.csv`**: CSV file storing silhouette scores for different values of K.
- **`clustered_data_with_centroids.csv`**: CSV file with clustered data and centroids.

## Results
The analysis identifies clusters of customers based on spending patterns and income. Key insights include:
- Optimal number of clusters based on silhouette scores and WCSS.
- Visualizations of clusters in 2D and 3D, showing distinct customer groups.

## Contributing
Contributions are welcome! If you find a bug or want to add features, please create an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
