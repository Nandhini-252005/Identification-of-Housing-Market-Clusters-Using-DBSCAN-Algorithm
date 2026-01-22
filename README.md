# Housing Market Analysis using DBSCAN Clustering

This project applies **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** to analyze and segment housing market data. The goal is to identify dense clusters of similar housing properties and detect outliers in the real estate market. The project is implemented using Python in a Jupyter Notebook for educational and analytical purposes.

---

## Project Overview

Housing market data often contains complex patterns influenced by location, pricing, and property features. Traditional clustering methods may struggle with irregular cluster shapes and outliers.

In this project:
- Housing data is explored and preprocessed
- **DBSCAN clustering** is applied to group similar housing properties
- Outliers (noise points) are identified to highlight unusual properties
- Results are visualized to gain insights into housing market trends

---

## Algorithm Used

### DBSCAN (Density-Based Clustering)
- Unsupervised learning algorithm
- Groups data points based on density
- Requires two main parameters: `eps` and `min_samples`
- Automatically identifies noise and outliers
- Effective for non-linear and irregular clusters

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

---

## Repository Structure

```text
housing-market-clustering-dbscan/
│── housing_market_using_DBSCAN.ipynb
│── README.md
