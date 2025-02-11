📌 Project Title: Human Activity Recognition (HAR) Using Machine Learning and Deep Learning
📌 Overview
This project aims to classify human activities (walking, sitting, standing, etc.) using sensor data (accelerometer & gyroscope) from the UCI HAR dataset. We implemented both Machine Learning (SVM, Random Forest, Logistic Regression) and Deep Learning (LSTM, CNN) models to compare their effectiveness in human activity recognition.

📌 Dataset: UCI HAR Dataset
Collected using: Samsung Galaxy S II smartphone
Data Type: Accelerometer & Gyroscope signals
Activities Monitored:
✅ Walking
✅ Walking Upstairs
✅ Walking Downstairs
✅ Sitting
✅ Standing
✅ Lying Down
📌 Dataset Structure
X_train.txt & X_test.txt → Sensor features (561 features per sample)
y_train.txt & y_test.txt → Activity labels
features.txt → Names of 561 extracted features
subject_train.txt & subject_test.txt → Subject IDs for tracking participants

📌 Results & Model Comparison
Model	Accuracy
✅ SVM (Best ML Model)	95.12%
Random Forest	92.5%
Logistic Regression	95%
LSTM (Best DL Model)83%
✅ CNN	99.52%
🔹 1D CNN performed the best, followed by LSTM.
🔹 SVM outperformed all traditional ML models.
