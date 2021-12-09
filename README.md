## Welcome to Clustering (Theory & Code)

### 01 Unsupervised Learning (Theory)
* What is Unsupervised Learning & Goals of Unsupervised Learning 
* Type of Unsupervised Learning: 1.Clustering, 2.Association Rule & 3.Dimensionality Reduction

### 02 Clustering (Theory)
* Definition and Application of Clustering
* 4 methods: 1.K Means 2.Hierarchical 3.DBScan & 4.Gaussian Mixture

### 03 Euclidean & Manhattan Distance (Theory)
* Two points are near to each other, chances they are similar
* Distance Measure between two points
  1. Euclidean Distance: Under-root of Square distance between two points
  2. Manhattan Distance: Absolute Distance between points 

### 04 K-Means Clustering (Theory)
* How Algorithim works (Step Wise Calculation)
* Pre-processing required for K Means
* Determining optimal number of K: 1.Profiling Approach & 2.Elbow Method

### 05 Elbow Method (Theory)
* Working of Elbow Method with Example
* 3 concepts: 1.Total Error, 2.Variance/Total Squared Error & 3.Within Cluster Sum of Square (WCSS)

### 06 K Means Clustering (Python Code)
* Define number of clusters, take centroids and measure distance
* Euclidean Distance : Measure distance between points
* Number of Clusters defined by Elbow Method
* Elbow Method : WCSS vs Number of Cluster
* Silhouette Score : Goodness of Clustering

### 07 Hierarchical Clustering (Theory)
* Two Approaches: 1.Agglomerative(Botton-Up) & 2.Divisive(Top-Down)
* Types of Linkages: 
  1. Single Linkage - Nearest Neighbour (Minimal intercluster dissimilarity)
  2. Complete Linkage - Farthest Neighbour (Maximal intercluster dissimilarity)
  3. Average Linkage - Average Distance (Mean intercluster dissimilarity)
* Steps in Agglomerative Hierarchical Clustering with Single Linkage
* Determining optimal number of Cluster: Dendogram  

### 08 Dendogram (Theory)
* Hierarchical relationship between objects
* Optimal number of Clusters for Hierarchical Clustering

### 09 Hierarchical Clustering (Python Code)
* Type of HC
    1. Agglomerative : Bottom Up approach
    2. Divisive : Top Down approach
* Number of Clusters defined by Dendogram
* Dendogram : Joining datapoints based on distance & creating clusters
* Linkage : To calculate distance between two points of two clusters
    1. Single linkage : Minimum Distance between two clusters
    2. Complete linkage : Maximum Distance between two clusters
    3. Average linkage : Average Distance between two clusters

### 10 DBScan Clustering (Theory)
* Density Based Clustering
* Kmeans & Hierarchical good for compact & well seperated Data
* Both are sensitive to Outliers & Noise
* DBScan overcome all the issue & works well with Outliers
* 2 important parameters - 
  1. eps: Distance between 2 points is lower/equal to eps they are neighbours
  2. MinPts: Minimum number of neighbours/data points with eps radius

### 11 DBScan Clustering (Python Code)
* No need to give pre-define clusters
* Distance metric is Euclidean Distance
* Need to give 2 parameters
    1. eps : Radius of the circle
    2. min_samples : minimum data points to consider it as clusters

### 12 GMM Clustering (Theory)
* Weakness of K Means
* Expectation Maximization(EM) method

### 13 Gausian Mixture Model Clustering (Python Code)
* Probablistic Model
* Uses Expectation-Minimization (EM) steps:
    1. E Step : Probability of datapoint of each cluster
    2. M Step : For each cluster,revise parameter based on proabability

### 14 Cluster Adjustment (Theory)
* 2 Steps we normally do for Cluster Adjustement 
  1. Quality of Clustering (Cardinality & Magnitude)
  2. Performance of Similiarity Measure (Euclidean Distance)

### 15 Silhouette Coefficient - Cluster Validation (Theory)
* Clusters are well apart from each other as the silhouette score is closer to 1
* It is a metric used to calculate the goodness of a clustering technique 
* Its value ranges from -1 to 1.
    1. 1: Means clusters are well apart from each other and clearly distinguished
    2. 0: Means clusters are indifferent, or distance between clusters is not significant
    3. -1: Means clusters are assigned in the wrong way

### 16 Disadvantage & Choosing Right Clustering Method (Theory)
* Disadvantage of each clustering techniques respectively 
* Based on the data, which is the right clustering method

### 17 Clustering Revision (Theory)
* Short Description of Each Clustering Alogrithim
* Advantage, Disadvantage
* When to use what

### 18 Interview Questions on Clustering (Theory)
* Commonly asked question on Clustering

### 19 K Modes (Theory)
* For Categorical variable clustering, use K Modes
* It uses the dissimilarities(total mismatch) between data points
* Lesser the dissimilarities, the more our data points are closer
* It uses Mode for most value in the column

### 20 K Modes (Python Code)
* K Mode code in Python
