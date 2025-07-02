🔍 Anomaly Detection in Neural Networks
This project demonstrates how Autoencoders, a type of neural network, can be used for Anomaly Detection in network intrusion data. The model is trained using the KDD Cup '99 dataset, and includes both unsupervised and supervised learning techniques. A user-friendly frontend is built using Streamlit, allowing users to easily interact with the model and detect anomalies from uploaded data in real-time.

📌 Features
Autoencoder-based Unsupervised Anomaly Detection

Comparative visualizations with:

Isolation Forest

One-Class SVM

Dimensionality reduction with PCA for 2D visualization

Streamlit frontend for real-time anomaly prediction

Modular and scalable codebase

🧠 Learning Paradigms Used
🔹 Supervised Learning
Utilized for evaluating performance (using is_attack labels in the dataset).

Metrics like accuracy, precision, recall, and F1-score help compare models.

🔹 Unsupervised Learning
Primary method used for anomaly detection.

Autoencoders learn to reconstruct normal data; high reconstruction error indicates anomalies.

Also implemented: Isolation Forest & One-Class SVM (pure unsupervised techniques).

🖥️ Frontend Integration
A sleek Streamlit-based UI is included for:

Uploading datasets

Triggering predictions

Viewing anomaly detection results visually

📡 How It Works:

The frontend sends data to the backend via HTTP requests.

Backend processes data using the trained autoencoder.

Results are returned and displayed with visual indicators.

📂 Dataset
Source: KDD Cup 1999 Dataset

Used the kddcup.data_10_percent_corrected subset

41 features + label (normal or attack)

📊 Visualizations Included
PCA 2D Scatter plots (colored by anomaly detection)

Comparison of Autoencoder vs Isolation Forest vs One-Class SVM

Reconstruction error distributions

🚀 How to Run the Project
⚙️ Backend (Autoencoder Training)
bash
Copy
Edit
python autoencoder_train.py
💡 Frontend (Streamlit App)
bash
Copy
Edit
streamlit run app.py
📁 Folder Structure
python
Copy
Edit
📦 anomaly-detection-neural-network
├── archive.zip
├── autoencoder_train.py
├── models/
├── app.py
├── utils/
├── README.md
🧰 Technologies Used
Python

Pandas, NumPy, Scikit-learn

TensorFlow / Keras

Matplotlib, Seaborn

Streamlit (for frontend)

✅ Future Improvements
Add LSTM-based anomaly detection for time-series

Extend to real-time network packet monitoring

Deploy as a full-stack web app with backend API

🧑‍💻 Author
Ronak Kumar
Computer Science Engineering (CSE), UPES
GitHub | LinkedIn
