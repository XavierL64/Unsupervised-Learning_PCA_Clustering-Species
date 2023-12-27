# Unsupervised-Learning_PCA_Clustering-Species

**Description**

This project leverages the sklearn preprocessing, decomposition, and clustering packages to identify groups based on data collected about pengouins in Antarctica. We take the following steps:

- Clean the dataset by removing missing values and outliers.
- Pre-process the data using standard scaling and one-hot encoding to add dummy variables.
- Perform Principal Component Analysis (PCA) on the dataset to reduce the number of components.
- Determine an optimal number of clusters and fit a KMeans cluster model on the reduced dataset.

**Dataset**

Data was collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network.

The dataset consists of 5 columns.

- culmen_length_mm: culmen length (mm)
- culmen_depth_mm: culmen depth (mm)
- flipper_length_mm: flipper length (mm)
- body_mass_g: body mass (g)
- sex: penguin sex
