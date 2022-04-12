# Exploring Neo4j and Graph Data Science for Fraud Detection


This repository contains the notebook for reproducing the fraud detection analysis covered in [this blog series](https://neo4j.com/developer-blog/exploring-fraud-detection-neo4j-graph-data-science-summary/). To summarize, This analysis uses [Neo4j and Graph Data Science (GDS)](https://neo4j.com/docs/graph-data-science/current/) to explore an anonymized data sample from a Peer-to-Peer (P2P) payment platform.  The notebook is split up into the following sections (mirroring the blog series) to cover various stages of the graph data science workflow:

- Part 1: Exploring Connected Fraud Data
- Part 2: Resolving Fraud Communities using Entity Resolution and Community Detection
- Part 3: Recommending Suspicious Accounts With Centrality & Node Similarity
- Part 4: Predicting Fraud Risk Accounts with Machine Learning


## Anonymized Peer-to-Peer (P2P) data
To run the notebook you will need a copy of the dataset which is available in the form of a neo4j dump file [in this folder](https://drive.google.com/drive/folders/1LaNFObKnZb1Ty8T7kPLCYlXDUlHU7FGa?usp=sharing). The folder also contains a readme with more details on the dataset and directions for how to load the data into neo4j if you are unfamiliar with load process. The folder contains the ODC-BY license for the dataset as well (seperate from the license in this repository).
