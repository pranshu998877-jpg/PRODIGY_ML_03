# PRODIGY_ML_03 - Cats and Dogs Classification using SVM

This repository contains the solution for **Task-03** of the Machine Learning Internship at **Prodigy InfoTech**.

## 📌 Project Overview
The objective of this task is to build a Support Vector Machine (SVM) classifier to distinguish between images of cats and dogs using a subset of the Kaggle dataset.

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python
* **Libraries:** 
  * `cv2` (OpenCV) for image loading and preprocessing
  * `scikit-learn` for the SVM classifier (`SVC`) and metrics
  * `matplotlib` & `seaborn` for plotting confusion matrix and sample predictions

## 📊 Methodology & Steps
1. **Data Preprocessing:** Loaded pet images, resized them to $64 \times 64$ pixels in grayscale, flattened the arrays, and normalized pixel values.
2. **Train-Test Split:** Split the dataset into 80% training and 20% testing sets.
3. **Model Training:** Trained a Support Vector Machine (SVM) model using the RBF kernel.
4. **Evaluation:** Evaluated model performance using Accuracy Score, Classification Report, Confusion Matrix, and visual sample predictions.

## 🚀 How to Run the Code
1. Clone the repository:
   ```bash
   git clone [https://github.com/pranshu998877-jpg/PRODIGY_ML_03.git](https://github.com/pranshu998877-jpg/PRODIGY_ML_03.git)
