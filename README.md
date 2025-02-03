# Data-Science-Projects

##1. Semantic Clustering for Product Recommendation using MiniLM & Spark
This project builds a scalable recommendation system using sentence embeddings, PCA, and KMeans clustering in PySpark. It leverages the all-MiniLM-L6-v2 transformer to generate semantic embeddings for product descriptions, then applies PCA for dimensionality reduction and KMeans to cluster similar products. The system enables efficient content-based recommendations by retrieving items from the same cluster.

🔹 Technologies Used: PySpark, Sentence Transformers, KMeans, PCA
🔹 Key Features:
✔️ Semantic embeddings for product descriptions
✔️ KMeans clustering for grouping similar products
✔️ PCA for dimensionality reduction
✔️ Scalable processing with PySpark
✔️ Efficient content-based recommendations

🚀 Future Enhancements:
🔹 Hybrid Approach – Integrating collaborative filtering (ALS in Spark MLlib) to combine user behavior with content-based recommendations.
🔹 Cosine Similarity – Fine-tuning recommendations within clusters.
