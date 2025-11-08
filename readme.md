# Graph-Based Anomaly Detection on Credit Card Transactions  
This project applies **network analysis** and **PageRank-based anomaly detection** to identify unusual spending patterns in a large **credit card transaction dataset**.

We construct a **bipartite graph** linking **Cardholders ↔ Vendors**, compute **weighted PageRank**, model its expected relationship with node degree, and flag anomalies based on extreme residuals.  

The analysis is performed **month-by-month** to capture patterns over time and reveal persistent or emerging suspicious behavior.


### Notebook
You can view the full notebook here:  

[fraud-detection-pagerank.ipynb](fraud-detection-pagerank.ipynb)  