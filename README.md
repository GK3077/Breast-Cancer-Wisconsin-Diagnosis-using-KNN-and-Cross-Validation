# Breast Cancer Wisconsin Diagnosis using KNN and Cross Validation
This repository contains a Python implementation of a Breast Cancer Wisconsin Diagnosis classifier using the K-Nearest Neighbors (KNN) algorithm with cross-validation.

### Overview
Breast cancer diagnosis is a critical area in medical research. This project aims to predict whether a tumor is malignant (M) or benign (B) based on features extracted from digitized images of breast cancer masses.

### Requirements
To run this project, you need to have the following dependencies installed:

- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn

You can install these dependencies using pip:
```
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Dataset
The dataset used in this project is available in data.csv. It contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. Features include mean, standard error, and "worst" or largest (mean of the three largest values) for various cell characteristics.

### Results
The optimal number of neighbors for the KNN classifier is determined using cross-validation. The misclassification error versus the number of neighbors plot helps in visualizing the performance of the model. In this case, the optimal number of neighbors is found to be 13.

### Contributing
Contributions are welcome! Please feel free to submit issues and pull requests.

### License
This project is licensed under the MIT License.
