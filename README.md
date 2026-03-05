# 🧑‍💻 HOG-Based Face Detector

## 📝 Project Overview
Development of a Computer Vision system for facial detection in images, utilizing HOG (Histogram of Oriented Gradients) feature extraction combined with a Support Vector Machine (SVM) classifier.

## 🎯 Objectives & Results
* **Feature Extraction:** Used HOG to extract visual features from faces (trained on the LFW - Labeled Faces in the Wild dataset).
* **Classification:** Trained a LinearSVC model.
* **Sliding Window:** Implemented a detector that scans portions of a test image to identify and highlight found faces (drawing red bounding boxes).

## 🛠️ Technologies & Libraries
* Python
* Scikit-Image (HOG, view_as_windows)
* Scikit-Learn (LinearSVC)
* Matplotlib (Patches)
