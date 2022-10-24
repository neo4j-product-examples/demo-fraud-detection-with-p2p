# Exploring Neo4j and Graph Data Science for Fraud Detection


This repository contains the notebook for reproducing the fraud detection analysis covered in [this blog series](https://neo4j.com/developer-blog/exploring-fraud-detection-neo4j-graph-data-science-summary/). To summarize, this analysis uses [Neo4j and Graph Data Science (GDS)](https://neo4j.com/docs/graph-data-science/current/) to explore an anonymized data sample from a Peer-to-Peer (P2P) payment platform.  The notebook (`fraud-detection-demo-with-p2p`) is split up into the following sections, mirroring the blog series, to cover various stages of the graph data science workflow:

- Part 1: Exploring Connected Fraud Data
- Part 2: Resolving Fraud Communities using Entity Resolution and Community Detection
- Part 3: Recommending Suspicious Accounts With Centrality & Node Similarity
- Part 4: Predicting Fraud Risk Accounts with Machine Learning


## Getting the Data
To run the notebook you will need a copy of the dataset which is available in the form of a neo4j dump file [in this folder](https://drive.google.com/drive/folders/1LaNFObKnZb1Ty8T7kPLCYlXDUlHU7FGa?usp=sharing). The folder also contains a readme with more details on the dataset and directions for how to load the data into neo4j if you are unfamiliar with the process. The folder contains the ODC-BY license for the dataset as well (separate from the license in this repository).


## Subdirectories & Variants
There are a couple subdirectories containing variants of the `fraud-detection-demo-with-p2p` notebook for various purposes:

- [./gds-v1.8](https://github.com/neo4j-product-examples/demo-fraud-detection-with-p2p/tree/main/gds-v1.8) contains a GDS 1.8 compatible version of the notebook. The notebook in the primary directory is built for GDS 2.x and will not work on GDS 1.8 or earlier versions.
- [./abridged-demo](https://github.com/neo4j-product-examples/demo-fraud-detection-with-p2p/tree/main/abridged-demo) contains a version of the notebook for a quick introductory demo.  Some steps have been removed and altered to shorten the notebook and others steps have been summarized/condensed. This notebook is also built for GDS 2.x and not 1.x compatible. 


