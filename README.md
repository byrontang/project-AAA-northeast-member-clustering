# project-AAA-northeast-member-clustering
In this repository, I presented my personal work done in the capstone project for **Postgraduate Diploma of Machine Learning and Artificial Intelligence** by **Colombia Engineering**.

## Overview
### Goal
The goal of this project is to provide market segmentation of AAA Northeast members that would help increase the penetration of AAA's financial products.

### Contents
- A final presentation deck in pdf that includes approach and analysis results and could be presented to business stackholders
- A jupyter notebook for data exploration and data preprocessing in Python
- A jupyter notebook for modeling, including predictive analysis and clustering, in Python

### Methodology
- **Predictive Analysis**: Classification model helps predict the probability of purchsing each product. The predicted probabilities are latter used for clustering. 

- **Clustering**: Clustering helps explore market segmentation and opportunities.

### Challenges
- **Unbalanced Data**: Most products have low penetration. Therefore, it creates unbalanced data when building classification models. To counter this issue, up-sampling is used in modeling process.

- **Model Improvement - AUC**: Several classification and ensemble models were applied to select best model. The best model and technique are identified in this project.

### Results
- The prediction performance turned out to be quite impressive, with **an average of 0.975 AUC** on test set across 9 products. The high AUCs gave me confidence to use the predicted probabilities of purchasing for clustering. 
- An ideal number of clustering is identified to **provide actionable recommendations and product strategy**.
