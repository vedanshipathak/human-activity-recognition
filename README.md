# Human Activity Recognition (HAR) Using Machine Learning and Deep Learning

## 📌 Overview
This project aims to classify human activities (walking, sitting, standing, etc.) using sensor data (accelerometer & gyroscope) from the UCI HAR dataset. We implemented both Machine Learning (SVM, Random Forest, Logistic Regression) and Deep Learning (LSTM, CNN) models to compare their effectiveness in human activity recognition.

## 📌 Dataset
- **Dataset Name:** UCI HAR Dataset  
- **Collected using:** Samsung Galaxy S II smartphone  
- **Data Type:** Accelerometer & Gyroscope signals  
- **Activities Monitored:**
  - ✅ Walking
  - ✅ Walking Upstairs
  - ✅ Walking Downstairs
  - ✅ Sitting
  - ✅ Standing
  - ✅ Lying Down

### 📌 Dataset Structure
| File Name | Description |
|-----------|-------------|
| `X_train.txt` & `X_test.txt` | Sensor features (561 features per sample) |
| `y_train.txt` & `y_test.txt` | Activity labels |
| `features.txt` | Names of 561 extracted features |
| `subject_train.txt` & `subject_test.txt` | Subject IDs for tracking participants |

## 📌 Models Implemented
### Machine Learning Models
- **Support Vector Machine (SVM)**
- **Random Forest**
- **Logistic Regression**

### Deep Learning Models
- **Long Short-Term Memory (LSTM)**
- **Convolutional Neural Network (CNN)**

## 📌 Results & Model Comparison
| Model | Accuracy |
|--------|-----------|
| ✅ **SVM (Best ML Model)** | 95.12% |
| Random Forest | 92.5% |
| Logistic Regression | 95% |
| LSTM | 83% |
| ✅ **CNN (Best Overall Model)** | 99.52% |

### 🔹 Key Findings:
- **1D CNN performed the best** among all models, achieving **99.52% accuracy**.
- **SVM outperformed other traditional ML models** with an accuracy of **95.12%**.
- LSTM had lower accuracy than CNN but is useful for capturing temporal dependencies in sensor data.

## 📌 Installation & Usage
### 📌 Prerequisites
Ensure you have the following dependencies installed:
```bash
pip install numpy pandas scikit-learn tensorflow keras matplotlib seaborn
```

### 📌 Running the Code
Clone the repository:
```bash
git clone https://github.com/your-username/HAR-ML-DL.git
cd HAR-ML-DL
```


## 📌 Future Enhancements
- Experiment with **transformer-based models** for HAR.
- Optimize deep learning models using **hyperparameter tuning**.
- Implement real-time activity recognition using **IoT devices**.


## 📌 References
- UCI Machine Learning Repository: [https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)



