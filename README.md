# Spatial distribution of retail outlets

### Objective:
Analyse and visualize the spatial distribution of retail outlets covered by a retail firm across the regions of India.

### Tools
Python
* Dataframe - geopandas
* Visualization - leafmap

### Steps
1. Create a new environment to install geo-libraries
2. Import libraries
3. Load shapefile with regions
4. Load data with outlets
5. Distribution of outlets across regions
    1. Point-in-Polygon Analysis
        * Point-in-Polygon Analysis - A spatial analytic technique in which points from one feature dataset are overlaid on the polygons of another to determine which points are contained within the polygons.
        * Point -> Outlets | Polygon -> Region boundaries
    2. Nearest Neighbour Analysis

### Snapshots

<img src="https://user-images.githubusercontent.com/28645647/175801335-6ef7f5d3-c2b9-4eec-9f1e-49f6b009f85f.png" width="340px" height="400px">
<img src="https://user-images.githubusercontent.com/28645647/175801352-b1ad99cb-c014-42cc-aefb-95a855bd9bbd.png" width="380px" height="400px">

Distribution of outlets as cluster
<img src="https://user-images.githubusercontent.com/28645647/175801386-7ec15efa-d225-4fbc-b070-13e03fab6d64.png" width="600px" height="400px">

<!--![image](https://user-images.githubusercontent.com/28645647/175801335-6ef7f5d3-c2b9-4eec-9f1e-49f6b009f85f.png)
![image](https://user-images.githubusercontent.com/28645647/175801352-b1ad99cb-c014-42cc-aefb-95a855bd9bbd.png)

![image](https://user-images.githubusercontent.com/28645647/175801386-7ec15efa-d225-4fbc-b070-13e03fab6d64.png)-->
