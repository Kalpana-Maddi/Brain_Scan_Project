# 🧠 Brain MRI Segmentation using K-Means Clustering

## 📌 Project Overview

This project demonstrates how to apply **K-Means clustering**, an unsupervised machine learning algorithm, to segment **brain MRI images**.
The goal is to group pixels based on intensity similarity, creating clusters that represent major brain regions such as **gray matter, white matter, cerebrospinal fluid (CSF), and background**.

---

## ⚙️ Features

* Load and preprocess **DICOM** or standard image formats.
* Normalize and reshape images for clustering.
* Perform **K-Means clustering** to segment MRI images into `k` clusters.
* Visualize:

  * Original vs segmented brain images.
  * Individual cluster segments.
  * **Elbow Method** for optimal `k`.

---

## 🛠️ Technologies & Libraries

* **Python**
* `numpy` → Array operations & normalization
* `matplotlib` → Image visualization
* `scikit-learn (KMeans)` → Clustering algorithm
* `pydicom` → Read DICOM medical images
* `PIL (Pillow)` → Load and resize standard images

---

## 📂 Project Workflow

1. **Load the image** (DICOM or PNG/JPG).
2. **Normalize pixel values** (0–1 range).
3. **Reshape the image** into a 2D array for clustering.
4. **Apply K-Means clustering** to segment into `k` clusters.
5. **Visualize results**: segmented images, cluster-wise separation, and elbow plot.

---

## 📊 Results & Insights

* MRI image is simplified into **distinct tissue clusters**.
* **Elbow Method** helps determine the best number of clusters (`k`).
* Segmentation enhances **visualization of brain regions** and can aid in further medical analysis.

---

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/brain-mri-kmeans.git
   cd brain-mri-kmeans
   ```
2. Install dependencies:

   ```bash
   pip install numpy matplotlib scikit-learn pydicom pillow
   ```
3. Open the Jupyter/Colab notebook and run all cells.
