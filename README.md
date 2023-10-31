# Data-Visualization-on-NYC-AirBnB-Dataset

### 1. **Importing Libraries and Loading Data**
   - Libraries such as `pandas`, `numpy`, `folium`, `sklearn.cluster`, and others are imported.
   - Data is loaded from a CSV file into a DataFrame.

### 2. **HeatMap Generation**
   - A heatmap is generated using the latitude and longitude from the DataFrame, and the mean price is calculated for each location.
   - The heatmap is saved as an HTML file.

### 3. **Bar Plot of Average Price by Room Type**
   - A bar plot is created to visualize the average price of listings based on room types.

### 4. **Marker Cluster Map**
   - A map is created with marker clusters representing the top 10 most reviewed listings.
   - The map is saved as an HTML file.

### 5. **KMeans Clustering**
   - KMeans clustering is applied on the data considering longitude, latitude, price, and number of reviews.
   - A map is generated with clusters represented by different colors.
   - The map is saved as an HTML file.

### 6. **Elbow Method for Optimal k in KMeans**
   - The elbow method is applied to find the optimal number of clusters for KMeans.
   - A plot is generated showing distortions for different values of k.

### 7. **Hierarchical Clustering**
   - Dendrograms are created using hierarchical clustering.
   - Different metrics and transformations are applied, and dendrograms are saved as images.

### 8. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
   - A class `DBC` is defined to implement DBSCAN.
   - DBSCAN is applied on a synthetic dataset representing a face.
   - Snapshots of each step of DBSCAN are saved, and a GIF is created to visualize the clustering process.

### Code Structure
- The code is structured in a way that it sequentially performs various data visualization and clustering tasks.
- Different clustering algorithms such as KMeans, Hierarchical Clustering, and DBSCAN are applied and visualized.

### Conclusion
This code is focused on data visualization and clustering. It applies various clustering algorithms on different datasets and visualizes the results using maps, plots, and dendrograms. Ensure that the necessary data files and libraries are available, and the paths are correctly set to run this code successfully.
