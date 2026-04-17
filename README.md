# 🚨 Intrusion Detection System using UNSW-NB15 Dataset

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on network traffic data from the **UNSW-NB15 dataset** to understand patterns of normal and malicious activity. The goal is to prepare clean and meaningful data for building a **Machine Learning-based Intrusion Detection System (IDS)**.

---

## 🎯 Objectives

* Analyze network traffic features
* Identify patterns in malicious vs normal traffic
* Handle data imbalance
* Perform feature correlation analysis
* Prepare dataset for machine learning models

---

## 📂 Dataset

This project uses the **UNSW-NB15 Dataset**, a widely used dataset for intrusion detection research.

### 🔗 Dataset Source

* Kaggle Dataset (used in this project):
  👉 https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15

---

### 📊 Dataset Details

* Contains **2.5+ million records** of network traffic ([Kaggle][1])
* Includes **49 features** describing network behavior ([UNSW Sites][2])
* Covers **9 attack types**, including:

  * DoS
  * Exploits
  * Reconnaissance
  * Fuzzers
  * Backdoors
  * Worms ([UNSW Sites][2])

### 🏷️ Labels

* `label` → Binary classification (Normal / Attack)
* `attack_cat` → Multi-class attack categories

---

### ⚠️ Important Note

The dataset is **not included in this repository** due to its large size.
After downloading, place it inside:

```
data/
```

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

## 📊 Exploratory Data Analysis (EDA)

The notebook includes:

* 📥 Data loading and inspection
* 🧹 Data cleaning and preprocessing
* 📊 Feature distribution analysis
* ⚠️ Class imbalance visualization
* 🔗 Correlation heatmap
* 🏷️ Categorical feature analysis
* 🔄 Encoding for machine learning

---

## 📁 Project Structure

```
Intrusion_Detection/
│
├── Network_Traffic_UNSW_EDA.ipynb   # Main EDA notebook
├── README.md                       # Project documentation
└── data/                           # Dataset (add manually)
```

---

## 🚀 Getting Started

### 🔧 Prerequisites

Make sure you have:

* Python 3.x
* Jupyter Notebook / Google Colab

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

---

### 📥 Clone the Repository

```bash
git clone https://github.com/Keokhu/Intrusion_Detection.git
cd Intrusion_Detection
```

---

### 📊 Download Dataset

1. Visit the Kaggle link above
2. Download the dataset files
3. Place them inside the `data/` folder

---

### ▶️ Run the Notebook

```bash
jupyter notebook
```

Open:

```
Network_Traffic_UNSW_EDA.ipynb
```

---

## 📈 Key Insights

* Dataset contains both **normal and malicious traffic**
* Significant **class imbalance exists**
* Some features are highly correlated
* Categorical features require encoding before ML

---

## 🔮 Future Work

* Apply Machine Learning models:

  * Logistic Regression
  * Random Forest
  * XGBoost
* Handle imbalance using:
  * Class weighting
* Evaluate performance using:

  * ROC Curve
  * Precision / Recall / F1-score

---

## 🤝 Contributing

Feel free to fork this repository and contribute!

---

## 📜 License

This project is for educational purposes.

---

## 👨‍💻 Author

**Parth Bhavsar**

---


[1]: https://www.kaggle.com/datasets/alextamboli/unsw-nb15?utm_source=chatgpt.com "UNSW-NB15"
[2]: https://research.unsw.edu.au/projects/unsw-nb15-dataset?utm_source=chatgpt.com "The UNSW-NB15 Dataset"
