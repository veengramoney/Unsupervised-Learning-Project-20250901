# 🎯 Unsupervised Learning Project: Anime User Clustering & Recommendation

## 📘 Project Overview
This project applies unsupervised learning techniques to anime viewing data to:
- Cluster users based on genre preferences  
- Interpret dominant genres per cluster  
- Build a simple recommendation system  
- Export final results for sharing and analysis  

## 📂 Datasets Used
- `anime.csv`: Metadata including anime genres  
- `train_sampled.csv`: Sampled user ratings for memory efficiency  

## 🧠 Steps Performed

### 1. Genre Vectorization
- Cleaned and split genre strings  
- Created one-hot encoded genre vectors  

### 2. User Profiling
- Merged user ratings with genre vectors  
- Aggregated genre preferences per user  
- Normalized user profiles  

### 3. Dimensionality Reduction
- Applied PCA to reduce genre dimensions to 2D  

### 4. Clustering
- Used KMeans to cluster users based on genre preferences  
- Visualized clusters using PCA components  

### 5. Cluster Interpretation
- Analyzed dominant genres per cluster  
- Summarized top genres for each group  

### 6. Recommendation System
- Recommended genres for users based on their cluster assignment  

### 7. Final Exports
- Saved user profiles, cluster summaries, and recommendations to CSV  

## 🚀 How to Run the Notebook
1. Open the Jupyter notebook in your environment.  
2. Ensure the following files are in the correct path:  
   - `anime.csv`  
   - `train_sampled.csv`  
3. Run each cell sequentially.  
4. Outputs will be saved to the same project folder.

## 📁 Output Files
- `user_genre_profiles.csv`: Normalized genre preferences per user  
- `cluster_genre_summary.csv`: Average genre preferences per cluster  
- `top_genres_per_cluster.csv`: Top genres per cluster  
- `user_clusters.csv`: PCA components and cluster labels per user  
