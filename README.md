# 🌿 PlantVillage Leaf Disease Classification using CNN

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/caohuongquynh/PlantVillage/blob/main/plantvillageCNN_(1).ipynb)

## 📌 Project Overview
This project builds a Deep Learning classification pipeline using **Convolutional Neural Networks (CNN)** to identify **38 categories of plant leaf diseases** across 14 crop species from the **PlantVillage dataset**. The workflow covers automated data ingestion, Exploratory Data Analysis (EDA) across both disease classes and crop species, image preprocessing, and model training/evaluation.

## 📊 Exploratory Data Analysis (EDA)
* **Dataset Scale:** Over 54,000 leaf images categorized into **38 disease/healthy classes** (Model 2) and **14 crop types** (Model 1).
* **Distribution Insights:** Visualized class frequency and crop distribution to identify dataset imbalance (e.g., *Tomato* classes account for the largest portion of samples compared to minority crops).

## 🛠️ Tech Stack
* **Language:** Python 3
* **Deep Learning & Computer Vision:** TensorFlow / Keras, PIL / OpenCV
* **Data Manipulation & Visualization:** NumPy, Pandas, Matplotlib, Seaborn
* **Environment:** Google Colab (Tesla T4 GPU)[cite: 3] & Google Drive[cite: 1]

## 📈 Results
* **Validation / Test Accuracy:** **[Điền % độ chính xác mô hình của bạn, hoặc xóa dòng này nếu notebook chỉ dừng ở phần EDA]**
* Generated visual diagnostics including class distribution charts (`01_class_distribution.png`)[cite: 3] and sample leaf grids across categories[cite: 1].

## 🚀 How to Run
1. Click the **"Open In Colab"** badge above to launch the notebook directly in Google Colab.
2. Connect your Google Drive containing the `Plantvillage dataset` directory[cite: 1].
3. Run all cells (`Runtime -> Run all`) to reproduce the data analysis, visualizations, and model pipeline[cite: 1].
