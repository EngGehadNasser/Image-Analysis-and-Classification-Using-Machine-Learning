# Image-Analysis-and-Classification-Using-Machine-Learning

## **Project Overview**
This project focuses on analyzing and classifying digital images using machine learning techniques. The goal is to build a robust pipeline for loading, preprocessing, training, and evaluating classification models on image datasets. While this implementation uses the Naive Bayes algorithm as an example, the pipeline is designed to be flexible and adaptable to other machine learning models.

## **Key Features**
1. **Dataset Handling**:
   - Automatically loads images from class-specific directories.
   - Ensures balanced sampling by selecting a fixed number of samples per class.
   - Converts images to grayscale, resizes them, and normalizes pixel values for consistent input.

2. **Data Preprocessing**:
   - Flattens 2D image arrays into 1D feature vectors for compatibility with machine learning models.
   - Randomly shuffles the dataset to ensure unbiased splits during training and testing.

3. **Model Training and Evaluation**:
   - Implements stratified cross-validation to assess model performance consistently across different subsets of the data.
   - Evaluates model performance using metrics such as accuracy, precision, recall, and F1-score.
   - Generates a confusion matrix and classification report for detailed insights into model behavior.

4. **Visualization**:
   - Displays sample images from the dataset for better understanding.
   - Visualizes the confusion matrix using a heatmap for clear interpretation of classification results.
