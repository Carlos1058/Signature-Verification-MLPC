# Signature-Verification-MLPC
This program implements a **handwritten signature verification system** using the **MLPClassifier** from **scikit-learn**. It processes signature images by converting them to grayscale, resizing them to a fixed dimension, and flattening them into feature vectors for machine learning. The dataset consists of both **authentic** and **forged** signatures, labeled accordingly.  

The **MLPClassifier** is trained on this dataset to distinguish between real and fake signatures. It utilizes a multi-layer perceptron (MLP) neural network with **hidden layers and ReLU activation** to learn signature patterns effectively. The model is then evaluated on a test set using accuracy metrics.  

This approach provides a basic yet effective method for signature authentication, though further improvements, such as feature extraction using **HOG, SIFT, or deep learning (CNNs)**, could enhance its performance.
