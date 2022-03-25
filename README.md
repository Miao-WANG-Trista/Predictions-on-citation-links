# Predictions-on-citation-links
Kaggle link: https://www.kaggle.com/competitions/cs-mlns-22/overview
## Problem definition
The problem deals with a graph of a citation network where each node represents a research paper and the nodes are connected upon having the citations between the research paper. A complete graph is when all the research papers are rightly cited where due and one can analyse the graph to identify the most cited research paper and the areas of research inspired through citation. This connected graph canalso help in finding the correlated areas of research through interactions among them.
The data provided for the graph network, with 27770 nodes containing the title, year, journal, author and the abstract.
From the citations (edges) some edges were purposely removed and classifying whether there is an edge between two remaining nodes was the goal of this Kaggle competition.

## Preprocessing & Feature Engineering
In preprocessing: 
- stopwords removal
- stemming
- TF-IDF vectorization
- Word Embedding
- other miscellaneous actions

Feature Engineering:
Based on 5 initial features on each node, we created 33 features for each pair of nodes.
<img width="735" alt="image" src="https://user-images.githubusercontent.com/77568908/160103010-6fdb83ff-78e0-462b-8e2b-dfb9b0cb4936.png">
<img width="680" alt="image" src="https://user-images.githubusercontent.com/77568908/160103044-2824d24e-4164-40a2-b720-81bf399c5494.png">

## Modelling
The best performed classifiers are SVM and XGBoost. More details are attached in the report.pdf.
