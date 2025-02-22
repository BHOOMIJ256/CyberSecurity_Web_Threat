# Threat Detection System for Web Security
# 🚀 Project Overview 
This project aims to detect suspicious and malicious web interactions using machine learning techniques. The dataset, Cybersecurity: Suspicious Web Threat Interactions, is analyzed to classify normal and anomalous activities, helping in real-time cybersecurity monitoring.


# 🎯 Objectives

* **Identify anomalies** in web traffic that indicate potential cyber threats.

* Apply **machine learning and deep learning models** to classify web interactions as normal or malicious.

* Develop an adaptive system capable of detecting **zero-day attacks**.

# 📌 Features

**Anomaly Detection Models:**

> **Isolation Forest**

> **DBSCAN (Density-Based Spatial Clustering)**

> **Autoencoders (Deep Learning)**

**Feature Engineering:**

> **Session duration,end_time,total_bytes and time-based attributes>**

> **Standardization for better model performance.**

> **Label Encoding for Categorical Features.**

**Evaluation & Interpretation:**

> **Reconstruction error for Autoencoders**

> **Contamination tuning for Isolation Forest**

> **Hyperparameter tuning for DBSCAN**


# ⚙️ Tech Stack

* **Python (Pandas, NumPy, Scikit-Learn, TensorFlow, Matplotlib, Seaborn)**

* **Machine Learning (Supervised & Unsupervised Learning)**

* **Deep Learning (Autoencoders for anomaly detection)**

* **Data Preprocessing & Feature Engineering**

# 📊 Model Performance & Insights

Isolation Forest detected **28 anomalies** out of **282 records** i.e **9.93%** of the data.

**DBSCAN**  due to parameter sensitivity.

Autoencoders identified **15 anomalies**, providing a balanced detection mechanism.

**Threshold tuning in Autoencoders & Contamination adjustment in Isolation Forest improved detection accuracy**.

# 🔧 Hyperparameter Tuning

**Isolation Forest**: n_estimators, contamination

**DBSCAN:** eps, min_samples

**Autoencoders:** layers, neurons, threshold



