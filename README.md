# 🧠 Digit Recognition Dashboard

An interactive machine learning dashboard built with **Streamlit**, **TensorFlow**, and **Scikit-learn** for handwritten digit recognition, clustering, and visualization using the MNIST dataset.

The application allows users to train a Convolutional Neural Network (CNN), analyze model performance through visualizations, evaluate accuracy metrics, and test predictions on handwritten digits through an intuitive web interface.

---

## 📸 Application Preview

### 📊 CNN Training & Evaluation

![Training Results]<img width="1497" height="802" alt="Screenshot 2026-06-18 215941 - Copy" src="https://github.com/user-attachments/assets/da5f5ece-ae53-427a-ad1f-af16d06d4415" />


### 🎯 Digit Prediction

![Digit Prediction]<img width="1299" height="856" alt="Screenshot 2026-06-18 220128" src="https://github.com/user-attachments/assets/0de8a014-1ebf-409a-b350-f8462ec32a09" />


### 📝 Dataset Preview

![Dataset Preview]<img width="1580" height="911" alt="Screenshot 2026-06-18 215522 - Copy" src="https://github.com/user-attachments/assets/9b35b2bb-3d55-4bcb-9811-8b5443f97998" />


### 📈 Accuracy Visualization

![Accuracy Graph]<img width="1027" height="763" alt="Screenshot 2026-06-18 220038" src="https://github.com/user-attachments/assets/27e17772-ebf9-49fc-bc55-58adf1798ca7" />


---

##  Features

### 🔹 Handwritten Digit Recognition
- CNN-based handwritten digit classification
- Trained on the MNIST dataset
- Real-time digit prediction
- Interactive model testing

### 🔹 Model Training Dashboard
- Adjustable epochs
- Adjustable batch size
- Adjustable learning rate
- Custom train/test subset sizes
- Random seed configuration

### 🔹 Performance Evaluation
- Training accuracy visualization
- Validation accuracy visualization
- Training loss visualization
- Validation loss visualization
- Test accuracy and loss metrics

### 🔹 Machine Learning Modules
- K-Means Clustering
- DBSCAN Clustering
- Classification Analysis
- Interactive Data Visualization

### 🔹 User-Friendly Interface
- Built using Streamlit
- Interactive controls
- Real-time updates
- Easy experimentation with hyperparameters

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries & Frameworks
- Streamlit
- TensorFlow
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Project Structure

```text
digit-recognition-dashboard/
│
├── app.py
├── app_cnn.py
├── app_classification.py
├── app_kmeans.py
├── app_dbscan.py
├── requirements.txt
└── streamlit_for_app_builder.ipynb
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/RohithaKavala/digit-recognition-dashboard.git
cd digit-recognition-dashboard
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

If Streamlit is not recognized:

```bash
python -m streamlit run app.py
```

---

## 📊 Dataset

This project uses the **MNIST Handwritten Digits Dataset**, one of the most widely used benchmark datasets in machine learning and deep learning.

Dataset Characteristics:

- 70,000 grayscale handwritten digit images
- Digits from 0–9
- Image size: 28 × 28 pixels
- Training and testing subsets
- Suitable for image classification tasks

---

## 🧠 CNN Workflow

1. Load and preprocess MNIST dataset
2. Build CNN architecture using TensorFlow/Keras
3. Train the model using configurable parameters
4. Evaluate model performance
5. Visualize accuracy and loss trends
6. Predict handwritten digits on unseen test images

---

## 📈 Model Evaluation Metrics

The dashboard provides:

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Training Loss
- Validation Loss
- Test Loss

Visualizations include:

- Accuracy vs Epoch Graph
- Loss vs Epoch Graph
- Prediction Results
- Training History

---

## 🎯 Learning Outcomes

This project demonstrates practical implementation of:

- Deep Learning
- Convolutional Neural Networks (CNN)
- Machine Learning
- Unsupervised Learning
- K-Means Clustering
- DBSCAN Clustering
- Hyperparameter Tuning
- Data Visualization
- Model Evaluation
- Streamlit Application Development

---

## 🔮 Future Enhancements

- Handwritten Digit Drawing Canvas
- Confusion Matrix Visualization
- Model Saving & Loading
- Advanced Model Architectures
- Additional Machine Learning Algorithms
- Cloud Deployment Support
- Enhanced Dashboard UI

---

## 👩‍💻 Author

**Rohitha Kavala**
 
---

## ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.

---
