# Clustering Algorithms Repository

A comprehensive collection of Jupyter notebooks demonstrating various clustering algorithms and their applications across different data types including images, audio, documents, and time series data.

## 📚 Contents

### 1. **K-Means Clustering (From Scratch)**
   - **File**: `kmeans_scratch.ipynb`
   - **Description**: Implementation of K-Means clustering algorithm from scratch without using libraries
   - **Topics**: Algorithm implementation, centroid initialization, distance metrics, convergence

### 2. **Hierarchical Clustering**
   - **File**: `hierarchical.ipynb`
   - **Description**: Exploration of hierarchical clustering methods including agglomerative and divisive approaches
   - **Topics**: Dendrograms, linkage methods, distance metrics, cluster cutting

### 3. **Gaussian Mixture Models (GMM)**
   - **File**: `gmm.ipynb`
   - **Description**: Probabilistic clustering using Gaussian Mixture Models
   - **Topics**: EM algorithm, soft clustering, probability distributions, model selection

### 4. **DBSCAN Clustering with PyCaret**
   - **File**: `dbscan_pycaret.ipynb`
   - **Description**: Density-based clustering using DBSCAN algorithm with PyCaret AutoML framework
   - **Topics**: Density-based clustering, noise detection, epsilon and min_points tuning, AutoML

### 5. **Image Clustering**
   - **File**: `image_clustering.ipynb`
   - **Description**: Clustering techniques applied to image data for segmentation and grouping
   - **Topics**: Feature extraction, color-based clustering, image segmentation, computer vision

### 6. **Audio Clustering**
   - **File**: `audio_clustering.ipynb`
   - **Description**: Clustering audio files based on acoustic features
   - **Topics**: Audio feature extraction, MFCC, spectral features, sound classification

### 7. **Document Clustering**
   - **File**: `document_clustering.ipynb`
   - **Description**: Text document clustering using NLP techniques
   - **Topics**: TF-IDF, word embeddings, topic modeling, text similarity

### 8. **Time Series Clustering**
   - **File**: `timeseries_clustering.ipynb`
   - **Description**: Clustering temporal data and time series patterns
   - **Topics**: DTW (Dynamic Time Warping), shape-based clustering, temporal patterns

### 9. **Anomaly Detection with PyOD**
   - **File**: `anomaly_pyod.ipynb`
   - **Description**: Outlier and anomaly detection using PyOD library
   - **Topics**: Outlier detection algorithms, anomaly scoring, unsupervised learning

## 🚀 Getting Started

### Prerequisites
- Python 3.11 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yash-kalathiya/clustering.git
cd clustering
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install jupyter numpy pandas matplotlib scikit-learn scipy seaborn
pip install pycaret pyod librosa opencv-python nltk
```

### Usage

Launch Jupyter Notebook:
```bash
jupyter notebook
```

Navigate to any notebook and run the cells sequentially.

## 📦 Dependencies

- **Core Libraries**: numpy, pandas, scikit-learn, scipy
- **Visualization**: matplotlib, seaborn
- **Machine Learning**: pycaret, pyod
- **Domain-Specific**: 
  - Image: opencv-python, pillow
  - Audio: librosa, soundfile
  - Text: nltk, gensim
  - Time Series: tslearn

## 🎯 Key Concepts Covered

- **Distance Metrics**: Euclidean, Manhattan, Cosine similarity
- **Clustering Algorithms**: K-Means, Hierarchical, DBSCAN, GMM
- **Evaluation Metrics**: Silhouette score, Davies-Bouldin index, Calinski-Harabasz index
- **Feature Engineering**: PCA, t-SNE, feature extraction for different data types
- **Anomaly Detection**: Isolation Forest, Local Outlier Factor, One-Class SVM

## 📊 Results

Each notebook contains:
- Data exploration and preprocessing
- Algorithm implementation and parameter tuning
- Visualization of clusters
- Performance evaluation
- Interpretation of results

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is open source and available for educational purposes.

## 👤 Author

**Yash Kalathiya**
- GitHub: [@yash-kalathiya](https://github.com/yash-kalathiya)

## 📧 Contact

For questions or feedback, please open an issue in the repository.

---

⭐ If you find this repository helpful, please consider giving it a star!