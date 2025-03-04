# BA-820-Final-Project
# Airbnb California Market Segmentation & Housing Information Analysis
This repository contains .ipynb file of an analysis of the Airbnb California Market Segmentation & Housing Information Analysis using Google Colab.

# Contributing Team Members
Lifu Li, Wenxin Liang, Yu Xu, Dizhao Zhang, Huawan Zhong

# Google Colab Link
Merge data:
https://colab.research.google.com/drive/15_O9pQ1DDRU94eIZfmpLAn0kzBoH7TCT#scrollTo=3VM3x9BWXjH  
Part1:
https://colab.research.google.com/drive/1wLatciW1jFsbPGlgqjY-xrWGSWWuDsvZ?usp=drive_link  
Part2:
https://colab.research.google.com/drive/1LJMgdWjX9w6IMkgQjdjtGqrhbOR6OVTD#scrollTo=UlYdaxCCkjsA  
Part3: 
https://colab.research.google.com/drive/1Tqf8RGKyQcotI09tu3odc3t6YNo7WZIu
Part4:
https://colab.research.google.com/drive/1r-le8qpvhVpFHC2HSqTHqhbXzBsmzUN4#scrollTo=kJX9t3tamCJu

Merge data: This notebook is for merging datasets from all 8 cities and finally generalize the California dataset as the raw data.  
**"<EDA:Preproccessing:PCA:UMAP:HierarchicalClustering:KMeansClustering>_team9.ipynb"**: This notebook served as Part 1 of our project, mainly for EDA, Data Preprocessing, Normalization, Hierarchical Clustering and K-Means Clustering with PCA and UMAP.    
**"<UMAP:KPrototypeClustering>_team9.ipynb"**: This notebook served as Part 2 of our project, which is designed specifically for K-Prototype Clustering with UMAP to enhance computational efficiency. To maintain data consistency, the EDA, Data Preprocessing, and Normalization steps from Part 1 have been retained.   
**"<EDA:datacleaning/association_rule_for_k_prototype>_team9.ipynb"**: This notebook served as Part 3 of out project, which is designed specifically for association rules analysis for K-Prototype cluaters. In this notebook, two tables were merged to get rows with right clusters. And several data cleansing were made, such as drop duplicates and drop null values.   
**"<EDA/Textcleaning/Tokenization/Vectorization/TopicModeling/Visualization>_team9.ipynb"**: This notebook served as Part 4 of out project, which is designed specifically for text mining (Topic Modeling) analysis for K-Prototype cluaters. In this notebook, two tables were merged to get rows with right clusters. And visualizations of different clusters and topics scores were illustrated in the end.   

# License
This project uses the MIT license, people are free to work on the file and contribute. The file is not a finished product, and it would be interesting to see what insights others can identify.

# Key Finding
Our analysis revealed a strong alignment between clustering results and text mining insights, validating the segmentation of house listings into three distinct clusters: high-end & premium accommodations, mid-range & budget-friendly options, and compact & flexible stays. Association rule mining further reinforced these distinctions, showing that high-end listings commonly feature luxury amenities (e.g., dishwashers, cooking basics), while mid-range options emphasize practicality (e.g., microwaves, irons), and compact listings prioritize affordability (e.g., free street parking, long-term stays allowed). Topic modeling analysis highlighted that Cluster 0 focuses on comfort and premium experiences, Cluster 1 emphasizes accessibility and convenience, and Cluster 2 lacks distinctive thematic features. These findings provide actionable insights for both Airbnb and hosts—enabling personalized pricing recommendations, targeted marketing strategies, and optimized property descriptions to enhance booking efficiency and customer satisfaction.
