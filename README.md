# 🕵 Crime in San Francisco - Data Analysis with Clustering

This project explores crime incident data in San Francisco through data cleaning, visualization, and clustering techniques. The notebook processes real-world data to uncover trends, patterns, and geographic clusters of criminal activity.

## 🧠 Algorithms & Techniques Used (continued)

- *Exploratory Data Analysis (EDA):*
  - Used seaborn and matplotlib to visualize:
    - Boxplots of numerical features (e.g., hour, day, coordinates)
    - Bar plots of top crime categories
    - Time series trends of crime counts by category

- *Clustering:*
  - *K-Means Clustering:*
    - Applied on spatial coordinates (X, Y) and time-based features to group similar incidents
  - *K-Medoids Clustering:*
    - Used as an alternative to K-Means for more robust cluster centers
    - Imported from scikit-learn-extra
  - Cluster results can help identify crime hotspots and behavioral patterns
  - *XGboost*

## 🛠 Technologies Used

- Python 3.x  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- scikit-learn  
- scikit-learn-extra (for K-Medoids clustering)

## 📌 Getting Started

To run the notebook locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Crime-in-San-Francisco.git
   cd Crime-in-San-Francisco
