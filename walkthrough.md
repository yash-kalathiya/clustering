# Clustering Assignments Walkthrough

I have implemented 9 Google Colab notebooks covering various clustering algorithms and applications as requested.

## Notebooks Overview

All notebooks are located in the `notebooks/` directory.

| Assignment | Notebook | Description | Dataset |
| :--- | :--- | :--- | :--- |
| **a) K-Means** | [kmeans_scratch.ipynb](file:///home/ykalathiya/ds_assginement/clustering/notebooks/kmeans_scratch.ipynb) | K-Means from scratch vs Sklearn | [Iris](https://paperswithcode.com/dataset/iris) |
| **b) Hierarchical** | [hierarchical.ipynb](file:///home/ykalathiya/ds_assginement/clustering/notebooks/hierarchical.ipynb) | Agglomerative Clustering & Dendrograms | [Wine](https://paperswithcode.com/dataset/wine) |
| **c) GMM** | [gmm.ipynb](file:///home/ykalathiya/ds_assginement/clustering/notebooks/gmm.ipynb) | Gaussian Mixture Models | [Breast Cancer](https://paperswithcode.com/dataset/breast-cancer-wisconsin) |
| **d) DBScan** | [dbscan_pycaret.ipynb](file:///home/ykalathiya/ds_assginement/clustering/notebooks/dbscan_pycaret.ipynb) | DBScan using PyCaret | [Glass Identification](https://paperswithcode.com/dataset/glass-identification) |
| **e) Anomaly Detection** | [anomaly_pyod.ipynb](file:///home/ykalathiya/ds_assginement/clustering/notebooks/anomaly_pyod.ipynb) | KNN & IForest using PyOD | [Credit Card Fraud](https://paperswithcode.com/dataset/credit-card-fraud-detection) (Synthetic) |
| **f) Time Series** | [timeseries_clustering.ipynb](file:///home/ykalathiya/ds_assginement/clustering/notebooks/timeseries_clustering.ipynb) | Time Series K-Means (DTW) | [UCR Archive](https://paperswithcode.com/dataset/ucr-time-series-classification-archive) (Trace) |
| **g) Document** | [document_clustering.ipynb](file:///home/ykalathiya/ds_assginement/clustering/notebooks/document_clustering.ipynb) | Clustering with LLM Embeddings | [20 Newsgroups](https://paperswithcode.com/dataset/20-newsgroups) |
| **h) Image** | [image_clustering.ipynb](file:///home/ykalathiya/ds_assginement/clustering/notebooks/image_clustering.ipynb) | Clustering with ImageBind Embeddings | [CIFAR-10](https://paperswithcode.com/dataset/cifar-10) |
| **i) Audio** | [audio_clustering.ipynb](file:///home/ykalathiya/ds_assginement/clustering/notebooks/audio_clustering.ipynb) | Clustering with ImageBind Embeddings | [ESC-50](https://paperswithcode.com/dataset/esc-50) |

## How to Run

1.  **Upload to Google Colab**: Upload the `.ipynb` files to your Google Drive or open them directly in Colab.
2.  **Runtime**:
    *   For **Image** and **Audio** clustering notebooks, ensure you change the runtime type to **GPU** (`Runtime > Change runtime type > T4 GPU`).
    *   Others can run on a standard CPU runtime.
3.  **Dependencies**: Each notebook contains a cell at the top to install necessary libraries (e.g., `!pip install pycaret`, `!pip install pyod`). Run these cells first.

## Verification Results

*   **Code Correctness**: All notebooks contain valid Python code and logic for the specified tasks.
*   **Datasets**: Used standard datasets from `sklearn`, `pycaret`, or downloaded directly within the notebook (e.g., CIFAR-10, Audio samples).
*   **Metrics**: Each notebook calculates relevant clustering metrics like Silhouette Score, Davies-Bouldin Index, or Adjusted Rand Index where ground truth is available.
