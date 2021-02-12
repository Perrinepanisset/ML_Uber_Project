## MACHINE LEARNING - UBER PICK UP HOT ZONES

### GOAL
Determining hot zones for drivers to be in at any time through Machine Learning Unsupervised Clustering Models

### CONTEXT

One of the main pain point that Uber's team found is that sometimes drivers are not around when users need them. 
Users are not ready to wait 10 to 15 minutes before being picked-up. Uber's research shows that users accept to wait 5-7 minutes, otherwise they would cancel their ride.

### USAGE

### 1.Uber_Pickups-Preprocessing.ipynb
Understanding and cleaning dataset. Selecting a givin day and then generalizing to a week.

- INPUT FILES : uber-raw-data-sep14.csv

- OUTPUT FILE :
  - uber_pickups_1_09_6PM.csv
  - uber_pickups_week36.csv

### 2.Uber_Pickups-DBSCAN-day_hour_selection.ipynb
Computing clustering with DBSCAN for the 1st of September at 6PM.

- INPUT FILES : uber_pickups_1_09_6PM.csv

- OUTPUT FILE : Scatter map of the different clusters

### 2.Uber_Pickups-Kmeans-day_hour_selection.ipynb
Computing clustering with KMeans for the 1st of September at 6PM.

- INPUT FILES : uber_pickups_1_09_6PM.csv

- OUTPUT FILE : Scatter map of the different clusters 'Kmeans_clustering-uber_pickups_1_09_6PM.html'

### 3.Uber_Pickups-DBSCAN-week_generalization.ipynb
Generalizing DBSCAN clustering for a week.

- INPUT FILES : uber_pickups_week36.csv

- OUTPUT FILE : Scatter map of the different clusters

### 3.Uber_Pickups-Kmeans-week_generalization.ipynb
Generalizing DBSCAN clustering for a week.

- INPUT FILES : uber_pickups_week36.csv

- OUTPUT FILE : Scatter map of the different clusters
