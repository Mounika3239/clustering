# Clustering Algorithm Demonstration

This project showcases the implementation and enhancement of the K-means clustering algorithm, focusing on the effects of centroid initialization methods on convergence rates.

---

## Implementation

- **K-means Clustering**:
  - Demonstrates the impact of randomly initialized centroids on convergence.
  - Compares multiple runs with varying initial centroids to analyze performance.

- **Enhanced Centroid Initialization**:
  - Implements a farthest-point strategy for better centroid selection.
  - Ensures reproducibility using serialized centroid data.

- **Performance Metrics**:
  - Records and compares iterations required for convergence under different initialization methods.

---

## Files in the Repository

- **`ClusteringDemo.ipynb`**: Jupyter notebook containing:
  - Implementation of the original K-means algorithm with random centroid initialization.
  - Modified version using farthest-point centroid initialization.
  - Performance comparison with visualizations.

- **`report.pdf`**: Detailed analysis and results of the clustering experiments.

---

## Prerequisites

- Python 3.x
- Required libraries:
  - `numpy`
  - `matplotlib`
  - `pickle`
  - `scikit-learn` (optional, for additional clustering support)

Install dependencies using:
```bash
pip install numpy matplotlib scikit-learn
