# Stampede Prediction using MCNN

This project uses a Multi-Column Convolutional Neural Network (MCNN) to predict potential stampede situations from crowd images.

## Key Features

* MCNN architecture for multi-scale crowd analysis
* K-Fold cross-validation for robust evaluation
* High performance (≈97% accuracy, ≈0.99 AUC)
* Confusion matrix, ROC curve, and training analysis
* Grad-CAM visualization for model interpretability

## Dataset

* Crowd images with labels (Safe / Stampede)

## Results

* Strong classification performance with minimal false negatives
* Consistent results across folds
* Model focuses on dense crowd regions (via Grad-CAM)

## Future Work

* Real-time video-based prediction
* Deployment for crowd monitoring systems
