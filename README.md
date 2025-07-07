# Project 4: Unsupervised Image Clustering and Visualization

This project applies unsupervised learning techniques to the MNIST dataset of handwritten digits. Using clustering and dimensionality reduction, we analyze patterns in the dataset without relying on labeled data.

## Project Overview

The goal of this project is to:

- Perform **K-Means clustering** to discover groupings in the data
- Apply **PCA** and **t-SNE** to visualize high-dimensional image data in 2D space
- Evaluate clustering performance using **silhouette score** and **confusion matrix**
- Gain insights into how unsupervised learning can be used for image analysis

## Technologies Used

- Python 3.x
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Dataset

We use the **MNIST digits dataset** available directly from `sklearn.datasets.load_digits`. This dataset contains 1,797 grayscale images of handwritten digits (0–9), each 8x8 pixels.

## Project Structure

```

├── README.md
├── Project-4-Unsupervised-Image-Clustering-and-Visualization.ipynb         # Full Jupyter notebook with code and outputs
└── requirements.txt        # List of required Python packages

````

## Getting Started

1. **Clone the repo:**
   ```bash
   git clone https://github.com/Samuel-Solomon-1/Project-4-Unsupervised-Image-Clustering-and-Visualization.git
   cd Project-4-Unsupervised-Image-Clustering-and-Visualization
   ````

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook:**

   ```bash
   jupyter notebook notebook.ipynb
   ```

## Results

* Optimal number of clusters: \~10 (via Elbow Method)
* Silhouette Score: A quantitative measure of clustering quality
* Visualized clusters using PCA and t-SNE in 2D
* Observed overlap between similar digits (e.g., 4 & 9, 3 & 8)

## Insights

* K-Means can uncover useful patterns in image data without labels.
* Dimensionality reduction greatly aids in understanding cluster relationships.
* This approach can be extended to more complex image datasets or combined with semi-supervised learning.


**Author:** \Samuel Solomon
