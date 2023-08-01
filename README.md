# machine_learning_project-unsupervised-learning

## Project Outcomes
- In this project,  unsupervised learning techniques to a real-world data set of "Wholesale Data". Data visualization tools was used to communicate the insights gained from the analysis.
- Goal: To analyze shoppers’ behavior by creating clusters of similar products base on their attributes.
### Duration:
Approximately 1 hour and 40 minutes
### Project Description:
The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project involves four main parts: 
1. Exploratory Data Analysis and  and Preprocessing
    - Import and clean the data sets
    - Analyze and visualize the relationships between the different variables using pairplot and heatmap
    - Handle missing values and outliers by performaing log-transform
    - Perform feature selection using random forest regression to understand the corellation of different feautures
    - Feature engineering with StandardScaler and PCA
2. KMeans clustering, 
    - Apply elbow Method to find optimal number of cluster
    - Create model and visualize clusters with their correlated centroid
3. Hierarchical clustering 
    - Create Dendrogram and finding optimal number of cluster
    - Create model and visualize clusters
4. PCA.
    - Create Scree plot to visualize explain variance ratio
    - Create bar charge in feature importants

### Results
- Fresh has the highest sale follow by grocery
- Kmeans cluster give optimal number of 4 distinct group of customer base on their shopping pattern.
- Kmeans cluster are more distinc than hierarchical clustering
- Having 3 principal components/features can still preserve approximately 90% of the prediction.
### Challenge
- Time constraint lead to less time dedicate to cleaning outlier. Perform log transform to penalize extreme outlier from impacting the model. However, there are still outlier in the log transform. IQR score can be used as the next step to process outlier.

### Future Goal
1. IQR Score to remove the outlier from the data to enhance the robustness of the model
2. Evaluate cluster model with inertia, the mean squared distance between each instance and its closest centroid
3. More time to evaluate PCA and find 3 feature that preserve the 90% of model prediction to provide insight for business strategies.

