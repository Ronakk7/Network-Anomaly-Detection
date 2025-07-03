# 🔍 Anomaly Detection in Neural Networks

This project demonstrates how **Autoencoders**, a type of neural network, can be used for **Anomaly Detection** on network intrusion data. The model is trained using the **KDD Cup '99** dataset, leveraging both **unsupervised** and **supervised** learning techniques. A user-friendly **Streamlit frontend** is integrated to allow real-time anomaly detection from uploaded data.

---

## 📌 Features

- 🧠 Autoencoder-based **Unsupervised Anomaly Detection**
- 📊 Comparative visualizations with:
  - Isolation Forest
  - One-Class SVM
- 📉 Dimensionality reduction with **PCA for 2D visualization**
- 🌐 **Streamlit frontend** for real-time anomaly prediction
- 🔁 **Modular and scalable** codebase for easy experimentation

---

## 🧠 Learning Paradigms Used

### 🔹 Supervised Learning
- Used for performance evaluation using `is_attack` labels.
- Metrics: Accuracy, Precision, Recall, F1-score.

### 🔹 Unsupervised Learning
- **Primary method** for anomaly detection.
- Autoencoders learn to reconstruct normal data → High reconstruction error = anomaly.
- Additional unsupervised methods:
  - Isolation Forest
  - One-Class SVM

---

## 🖥️ Frontend Integration

A sleek **Streamlit-based UI** is included for:

- 📁 Uploading datasets
- 🚀 Triggering predictions
- 📊 Viewing results with interactive visual indicators

### 🔗 How It Works:

1. The frontend sends data to the backend via HTTP requests.
2. Backend processes data using the trained autoencoder model.
3. Results are returned and displayed visually with anomaly markers.

---

## 📂 Dataset

**Source:** [KDD Cup 1999 Dataset](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)

- Subset used: `kddcup.data_10_percent_corrected`
- 41 Features + 1 Label (`normal` or `attack`)

---

## 📊 Visualizations

- PCA 2D scatter plots (colored by anomaly class)
- Comparison graphs: Autoencoder vs Isolation Forest vs One-Class SVM
- Histogram of reconstruction error distributions

---

## 🚀 How to Run the Project

### ⚙️ Backend (Model Training)
```bash
python autoencoder_train.py

💡 Frontend (Streamlit App)
streamlit run app.py
🧰 Technologies Used
Python (Data processing + model training)

Libraries:

Pandas, NumPy, Scikit-learn

TensorFlow / Keras

Matplotlib, Seaborn

Frontend:

Streamlit (UI interface)

✅ Future Improvements
🔁 Add LSTM-based anomaly detection for time-series data

📡 Integrate real-time packet monitoring

🌐 Deploy as a full-stack web app with backend APIs

🧑‍💻 Author
Ronak Kumar
B.Tech CSE, UPES
GitHub | LinkedIn



