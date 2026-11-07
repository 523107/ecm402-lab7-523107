# ECM-402: AI for Signal Processing – Lab 7

## Title
Implementation and Comparative Analysis of ICA, PCA, K-Means, Gaussian Mixture Models, Agglomerative Clustering, and Spectral Clustering.

## Objective
To implement and analyze different signal processing and machine learning techniques, including:
- Independent Component Analysis (ICA)
- Principal Component Analysis (PCA)
- K-Means Clustering
- Gaussian Mixture Models (GMM)
- Agglomerative Clustering
- Spectral Clustering

## Experiments Performed
1. Generated independent source signals and mixed them using a mixing matrix.
2. Applied FastICA to recover the original source signals.
3. Compared PCA and ICA for dimensionality reduction and source separation.
4. Studied ICA performance using Gaussian and non-Gaussian signals.
5. Generated digital modulation datasets (BPSK, QPSK, 8PSK, and 16QAM).
6. Extracted statistical features from the modulation signals.
7. Applied PCA and analyzed explained variance and reconstruction error.
8. Implemented K-Means clustering and evaluated different cluster counts.
9. Compared GMM and Agglomerative Clustering.
10. Compared K-Means and Spectral Clustering using a two-moons dataset.
11. Evaluated clustering robustness under different noise levels (SNR).

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- SciPy
- Google Colab

## Project Structure
```text
ecm402-lab7/
│
├── README.md
├── requirements.txt
├── lab7.ipynb
│
├── src/
│   └── main.py
│
└── results/
    ├── figures/
    └── tables/
```

## How to Run
1. Open `lab7.ipynb` using Google Colab or Jupyter Notebook.
2. Install the required libraries:
   `pip install -r requirements.txt`
3. Run the notebook cells sequentially to reproduce the experiments.
4. Generated figures and tables are saved in the results directory.

## Results
The experiments demonstrate:
- ICA can recover independent source signals from mixtures under suitable assumptions.
- PCA reduces dimensionality while retaining most of the data variance.
- K-Means, GMM, and Agglomerative Clustering provide different clustering approaches.
- Spectral Clustering performs better than K-Means on certain non-convex datasets.
- Clustering performance changes with noise levels.

## Conclusion
This lab demonstrates the application of independent component analysis, dimensionality reduction, and clustering techniques in signal processing. The experiments compare their performance and highlight their advantages and limitations on different datasets.

## Reproducibility
Random seeds were fixed where applicable to improve reproducibility of the experiments.
