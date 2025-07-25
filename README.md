# 🚨 Detection of Cyber Attacks on Web Applications using Machine Learning

This project aims to build an Intrusion Detection System (IDS) for web applications using machine learning techniques. It classifies network traffic as benign or malicious using models like SVM, Random Forest, and CNN. The system was trained and tested using the **CICIDS2017** dataset and achieved **95%+ accuracy** in identifying various cyber threats such as port scans and DDoS attacks.

---

## 📌 Features

- Detects various cyber attacks (e.g., Port Scan, DDoS, Brute Force).
- Supports multiple ML algorithms: SVM, Random Forest, and CNN.
- High accuracy and low false positive rate.
- Easy to integrate into security pipelines.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy** for data processing
- **Scikit-learn** for traditional ML models (SVM, Random Forest)
- **TensorFlow/Keras** for CNN-based deep learning
- **Matplotlib**, **Seaborn** for visualization
- **CICIDS2017 dataset** for training and evaluation

---

## 📊 Dataset

- **CICIDS2017**: A comprehensive dataset containing labeled data of benign and malicious network traffic.
- [Dataset Source](https://www.unb.ca/cic/datasets/ids-2017.html)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cyber-attack-detection-ml.git
   cd cyber-attack-detection-ml
