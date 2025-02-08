# Clustering-Antarctic-Penguin-Species

# Overview/Introduction

Researchers studying penguins in Antarctica have collected data on various physical characteristics of penguins, including culmen length, culmen depth, flipper length, and body mass. However, the species of each penguin was not recorded. The dataset includes three known species native to the region: Adelie, Chinstrap, and Gentoo. This project uses k-means clustering to identify groups within the dataset, helping researchers classify penguins into distinct clusters that may correspond to different species.

# Objectives

1. Preprocess the penguin dataset to prepare it for clustering.
2. Determine the optimal number of clusters using the Elbow Method.
3. Apply k-means clustering to group penguins based on their physical characteristics.
4. Visualize and analyze the clusters to assist researchers in identifying potential species groups.

# Data Source

The dataset, penguins.csv, contains the following columns:
  - culmen_length_mm: Length of the penguin's culmen (mm).
  - culmen_depth_mm: Depth of the penguin's culmen (mm).
  - flipper_length_mm: Length of the penguin's flipper (mm).
  - body_mass_g: Body mass of the penguin (grams).
  - sex: Sex of the penguin (MALE or FEMALE).

The data was collected by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network.

# Tools Used

- Python Libraries: Pandas, Matplotlib, Scikit-learn
- Clustering Algorithm: K-means clustering.
- Data Preprocessing: Standardization of features and creation of dummy variables for categorical data.
- Visualization: Scatter plots and the Elbow Method for determining the optimal number of clusters.

# Insights

1. Data Preprocessing:
    - The dataset was preprocessed by converting categorical variables (e.g., sex) into dummy variables and standardizing numerical features.
2. Optimal Number of Clusters:
    - The Elbow Method was used to determine the optimal number of clusters, which was found to be 4.
  
      ![d8](https://github.com/user-attachments/assets/85b271bb-0a1d-48e2-8f1b-fb48bc675f91)

3. Cluster Analysis:
    - Penguins were grouped into 4 clusters based on their physical characteristics.
    - The clusters were visualized using scatter plots, with culmen length as one of the key features.
  
      ![d9](https://github.com/user-attachments/assets/0df03d47-3c9a-4b96-ae8e-5aaf6d9ddb51)


# Key Findings

1. Optimal Clusters:
    - The optimal number of clusters identified was 4, suggesting that the penguins can be grouped into 4 distinct categories based on their physical traits.
2. Cluster Characteristics:
    - Each cluster has unique average values for culmen length, culmen depth, flipper length, and body mass, which may correspond to different species or subgroups.
3. Visualization:
    - Scatter plots revealed clear distinctions between clusters, particularly when plotting culmen length against cluster labels.

# Recommendations

1. Further Research:
    - Researchers should investigate whether the identified clusters correspond to the known species (Adelie, Chinstrap, and Gentoo) or if they represent subgroups within these species.
2. Additional Data:
    - Collect more data, such as genetic information or behavioral traits, to validate the clustering results and improve species classification.
3. Model Refinement:
    - Explore other clustering algorithms (e.g., DBSCAN, hierarchical clustering) to compare results and identify the most accurate grouping method.
4. Field Validation:
  - Use the clustering results to guide field observations and verify the accuracy of the groupings in real-world scenarios.

# How to Use This Repository

1. Clone the repository.
2. Install the required Python libraries (pandas, matplotlib, scikit-learn).
3. Run the Jupyter Notebook (Clustering Antarctic Penguin Species.ipynb) to reproduce the analysis.
4. Explore the dataset and modify the code to test different clustering algorithms or features.
