# Deep Learning, AI, Machine Learning  
### Unsupervised Learning, Recommenders, Reinforcement Learning

This repository contains graded assignments, implementations, and visualizations from the **Deep Learning AI Machine Learning Specialization**. It covers key topics in **unsupervised learning, recommender systems, and reinforcement learning**.

---

## 📂 Repository Structure

- **Unsupervised Learning**
  - K-means clustering
  - PCA (Principal Component Analysis)
  - Gaussian anomaly detection

- **Recommender Systems**
  - Content-based filtering (user/item neural networks)
  - Collaborative filtering
  - Retrieval and ranking pipelines

- **Reinforcement Learning**
  - Policy/value functions
  - Exploration vs. exploitation
  - Practical examples

---

## 🖼️ Visualizations

### K-means Clustering
- Cost function behavior across iterations  
- Elbow method for choosing optimal clusters  
- Cluster assignments and centroid updates  

### PCA
- Projection of high-dimensional data onto principal components  
- 2D and 3D scatter plots showing reduced dimensions  
- Variance explained by each component  

### Anomaly Detection
- Gaussian distributions for features (temperature, vibration)  
- Threshold selection using F1 score  
- Joint probability visualization for anomaly detection  

### Recommender Systems
- Neural network towers for user/item embeddings  
- Dot product similarity for rating prediction  
- Retrieval vs. ranking trade-offs  

---

## ⚙️ Key Implementations

- `find_closest_centroids()` → Assigns points to nearest centroid  
- `compute_centroids()` → Updates centroids by averaging assigned points  
- `estimate_gaussian()` → Estimates mean and variance for anomaly detection  
- `select_threshold()` → Chooses optimal epsilon using validation set F1 score  
- Neural network towers for recommender embeddings (`user_NN`, `item_NN`)  

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/ADVAIT135/Deep_Learning_AI_Machine_Learning-.git
