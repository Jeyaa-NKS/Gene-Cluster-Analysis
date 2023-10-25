# Gene-Cluster-Analysis

### Objective: 
The objective of this project was to perform gene expression analysis for the classification of cancer types using DNA microarray data. The dataset used in this analysis contains measurements of ALL (Acute Lymphoblastic Leukemia) and AML (Acute Myeloid Leukemia) samples from Bone Marrow and Peripheral Blood.

## Data Preprocessing

Data Loading: The project began with loading the gene expression data from the provided dataset files, including the training and test datasets, as well as the actual labels.

Data Cleaning: Data cleaning involved checking for missing values, handling object features, and extracting numerical features. The datasets were merged and split into training and test sets.

Feature Scaling: Standardization (scaling) of the features was performed to ensure that each feature has a mean of 0 and a standard deviation of 1.

## Exploratory Data Analysis

Principal Component Analysis (PCA): PCA was applied to reduce the dimensionality of the data while retaining 90% of the explained variance. The cumulative explained variance was visualized.

## Machine Learning Models

Decision Tree Classifier: A decision tree classifier was trained with a maximum depth of 3 and a minimum of 5 samples per leaf. It achieved an accuracy of 90%.

Random Forest Classifier: A random forest classifier with 100 estimators was trained and achieved an accuracy of 75%.

## Hierarchical Clustering

Dendrogram: A hierarchical clustering analysis was performed, and a dendrogram was generated to visualize the relationships between genes based on their expression profiles.
