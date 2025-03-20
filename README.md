# **Brain-Tumor-Classification-Using-SVM-mechansm**

This project aims to detect and classify brain tumors, specifically pituitary tumors, using Support Vector Machine (SVM) based on MRI scan images.

# 📂 Project Structure

# 📋 Project Overview

Brain tumors are abnormal growths in the brain that can be classified as malignant or benign. Early detection plays a crucial role in improving treatment outcomes. This project uses MRI images to classify brain tumors with the help of SVM for improved accuracy.

# **➤ Why SVM?**

**Better Generalization:** Unlike logistic regression, SVM prevents overfitting by optimizing both classification error and model complexity.

**Robust to Nonlinear Data:**  The RBF kernel in SVM efficiently handles complex decision boundaries for better classification.

# 🧠 Methodology

## Data Collection:

MRI scans dataset obtained from Kaggle.

1401 images used in total:

1222 for training (395 no tumor, 827 pituitary tumor)

179 for testing (105 no tumor, 74 pituitary tumor)

## Preprocessing:

Resizing images to 200x200.

Grayscale conversion and median filtering.

## Feature Extraction:

14 features extracted from MRI images; 4 prominent features identified for classification.

## Model Training:

Trained using linear function SVM with an 80:20 train-test split.

## Prediction & Evaluation:

Class 0: No Tumor

Class 1: Pituitary Tumor

# 📈 Results

Training Accuracy: Achieved using SVM with optimal hyperparameters.

Testing Accuracy: Slight variance (~3%) ensures better generalization than logistic regression.

# 🚀 How to Run

Clone the repository:

Install Dependencies:

Run the Jupyter Notebook:

Navigate to the tumor/proj folder.

Open Brain_Tumor_Classification.ipynb and run the code cells.

# 📝 References

Mayo Clinic - Pituitary Tumors

Scikit-learn Documentation

For further details, refer to the provided documentation in the project. 😊
