# 🧠 Anomaly Detection in Neural Networks

A comprehensive machine learning project focusing on **anomaly detection** using both supervised and unsupervised learning techniques. This project includes model training, evaluation, visual comparisons, and a fully functional **frontend interface** using **Streamlit** for real-time anomaly detection.

---

## 🚀 Project Overview

This project aims to identify anomalous behavior in a dataset by leveraging machine learning algorithms. It helps uncover patterns that deviate significantly from the norm, often indicating faults, frauds, or rare events.

---

## 🛠️ Features

- 📊 Model comparison across different ML algorithms
- 📉 Visualization of training and testing accuracies
- 🔍 Support for both **supervised** and **unsupervised** anomaly detection techniques
- 🌐 **Interactive frontend** built using **Streamlit** for real-time predictions
- 🔗 Seamless backend integration between the trained model and frontend UI

---

## 🧪 Algorithms Implemented

### ✅ Supervised Learning

These models are trained with labeled data (normal vs anomaly):

- Logistic Regression
- Random Forest
- Decision Tree
- XGBoost Classifier
- LightGBM Classifier

### 🧠 Unsupervised Learning

These models work without labeled data and learn normal patterns to detect outliers:

- Isolation Forest
- One-Class SVM
- Local Outlier Factor (LOF)
- Elliptic Envelope

---

## 📈 Visualizations

The notebook includes:

- Confusion matrices for each model
- Accuracy comparison bar plots
- ROC curves and AUC scores
- Training vs testing performance graphs

These help in better understanding model performance.

---

## 🌍 Streamlit Frontend

An **intuitive and user-friendly web interface** has been created using [Streamlit](https://streamlit.io/):

- Upload or input data
- Click "Detect Anomaly"
- Instantly view prediction results

> ⚙️ Streamlit sends data to the backend, where the best-performing trained model processes it and returns whether the input is **normal** or an **anomaly**.

---

## 💡 Technologies Used

| Category         | Tools/Technologies                             |
|------------------|------------------------------------------------|
| Language         | Python                                         |
| Data Handling    | Pandas, NumPy                                  |
| Visualization    | Matplotlib, Seaborn, Plotly                    |
| Machine Learning | scikit-learn, XGBoost, LightGBM                |
| Frontend         | Streamlit                                      |
| Others           | joblib (for model saving), pickle              |

---

## 📂 Project Structure

```
📦 Anomaly-Detection-NN
├── 📁 models/                  # Saved trained models
├── 📁 streamlit_app/           # Streamlit frontend code
├── 📊 results/                 # Visual outputs and reports
├── 📜 anomaly_detection.ipynb # Main Jupyter Notebook
├── 📄 README.md                # Project documentation
└── requirements.txt           # Python dependencies
```

---

## 📦 Installation & Running Locally

### 1. Clone the repo
```bash
git clone https://github.com/your-username/anomaly-detection-nn.git
cd anomaly-detection-nn
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit frontend
```bash
streamlit run streamlit_app/app.py
```

---

## 🧠 What is Anomaly Detection?

**Anomaly Detection** is the process of identifying rare items, events, or observations which raise suspicions by differing significantly from the majority of the data.

Applications include:

- Fraud detection in banking
- Network intrusion detection
- Industrial equipment fault detection
- Health monitoring systems

---

## 📚 Machine Learning Theory

### Supervised Learning 🔎

In supervised learning, models learn from labeled data (where anomalies are pre-identified). It includes classification models such as:

- **Logistic Regression**
- **Random Forests**
- **XGBoost**

### Unsupervised Learning 🔐

In unsupervised learning, models do not use labeled outputs. They detect patterns and spot outliers. This is useful when anomalies are **rare or unknown**. It includes:

- **Isolation Forest**: Splits data points recursively to isolate anomalies.
- **One-Class SVM**: Separates the data from the origin in a high-dimensional space.
- **LOF**: Measures local deviation of density from neighbors.
- **Elliptic Envelope**: Assumes data is Gaussian and fits an ellipse to it.

---

## ✨ Screenshots

<img src="results/accuracy_comparison.png" width="600"/>
<img src="results/confusion_matrix_xgboost.png" width="600"/>
<img src="streamlit_app/streamlit_ui.png" width="600"/>

---

## ✍️ Author

**Ronak**, BTech CSE @ UPES  
📧 Email: [ronakkumar3214@gmail.com](mailto:ronakkumar3214@gmail.com)  
🔗 LinkedIn: [Ronak Kumar](https://www.linkedin.com/in/ronak-kumar-9604b6256/)

---


## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome!

---

## ⭐ If you found this helpful

Please consider giving a ⭐ to this repository. It helps me grow and share more useful projects!

