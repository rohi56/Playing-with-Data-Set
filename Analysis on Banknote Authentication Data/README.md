# Clustering Analysis on Banknote Authentication Data

## Objective
The goal of this project is to apply unsupervised machine learning using KMeans Clustering on the Banknote Authentication dataset. This analysis seeks to uncover latent patterns in the data, which is especially valuable in situations where labeled data is scarce or unavailable. The ultimate aim is to help financial institutions detect counterfeit banknotes without relying on known classifications.

## Use Cases
🕵️ Fraud detection in financial systems

🧪 Early-stage clustering of novel or unseen transactions

🛠 Feature engineering for advanced authentication models

##  Dataset Summary
### Source: UCI Banknote Authentication Dataset

### Total Records: 1,372

### Features Used:

V1: Continuous numeric feature (likely from wavelet transform)

V2: Another derived continuous feature

### Preprocessing:

No missing values

No label column used (unsupervised clustering)

## 🔍 Analysis Methods
### Algorithm: KMeans Clustering from sklearn.cluster

### Approach:

* Load CSV into a Pandas DataFrame

* Apply KMeans clustering on features V1 and V2

* Assign cluster labels (0 or 1)

* Compute descriptive statistics for features across clusters

## 📈 Results Summary
KMeans effectively partitioned the dataset into two distinct clusters

Clusters revealed natural groupings in the data, which may correspond to genuine vs. forged notes

Features V1 and V2 showed significantly different distributions between clusters, indicating their usefulness in authentication tasks

## 🛠️ Technologies Used
Python

Pandas

Scikit-learn (KMeans)

Jupyter Notebook / PowerPoint for visualization

## 📁 Files Included
Banknote-authentication-dataset.csv: The input data file

Banknote_authentication_dataset.ipynb: Code and analysis notebook

Clustering Analysis on Banknote Authentication Data.pptx: Summary presentation of the analysis

## 📬 Contact
For questions or collaboration, feel free to reach out via GitHub or email.
