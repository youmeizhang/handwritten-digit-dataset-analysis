# handwritten-digit-dataset-analysis
This data analysis is based on dataA.mat and dataB.mat. DataB.mat is a handwritten dataset with 5 classes: digit 0, 1, 2, 3, 4. This repository mainly contains three parts.

Part I: Pre-processing of dataA
1. Find the problems of dataA (missing values, outliers)
2. Fix the detected problems (filling missing values, remove outliers)
3. Normalization. (min-max normalization, z-score normalization)

Part II: Dimensional reduction of dataB using PCA and LDA
1. Principal Component Analysis (PCA)
2. Naive Bayes Classifier for classification
3. Linear Discriminant Analysis (LDA)

Part III: Dimensional reduction of dataB using LLE and Isomap
1. Locally Linear Embedding (LLE)
2. Isomap
3. Naive Bayes Classification of digit 3 after dimensional reduction with PCA, LDA, LLE and Isomap respectively
