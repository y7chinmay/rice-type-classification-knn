# rice-type-classification-knn

This repository contains a machine learning project that uses the K-Nearest Neighbors (KNN) algorithm to classify rice grains into Basmati and Jasmine types based on morphological features extracted from their images

feat: Implement Rice Type Classification using KNN

This commit introduces a complete pipeline for classifying rice types (Basmati and Jasmine) based on extracted image features using a K-Nearest Neighbors (KNN) model.

Key features and steps include:
- Data Loading & Preprocessing: Unzipped rice image dataset and implemented image preprocessing steps (grayscale, blur, Otsu's thresholding) for individual rice grains.
- Feature Extraction: Developed logic to extract morphological features (area, perimeter, compactness, eccentricity) from rice grain contours.
- Data Preparation: Organized extracted features into a Pandas DataFrame, performed label encoding, and split the data into training and testing sets.
- KNN Model Development: Trained a K-Nearest Neighbors classifier on the extracted features.
- Model Evaluation: Assessed model performance using accuracy score, classification report, and a confusion matrix visualization.
- Prediction Function: Created a helper function (`predict_rice_type`) to take a new rice image, extract its features, and predict its type using the trained KNN model, along with visualizing the result.
