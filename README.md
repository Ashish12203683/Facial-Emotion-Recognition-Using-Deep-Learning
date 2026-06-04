# Facial Emotion Recognition Using Deep Learning

## 📌 Overview

This project implements and compares multiple Deep Learning architectures for Facial Emotion Recognition (FER). The goal is to classify human facial expressions into seven different emotion categories using image-based learning techniques.

The project progressively explores different neural network architectures, starting from a basic Perceptron model and advancing to Convolutional Neural Networks (CNN) and Transfer Learning using VGG16. A final comparative analysis evaluates the performance of all models to identify the most effective approach for emotion classification.

---

## 🎯 Objectives

- Detect and classify human emotions from facial images.
- Compare traditional neural networks with deep learning approaches.
- Evaluate the impact of transfer learning on classification performance.
- Identify the most accurate model for facial emotion recognition.

---

## 😊 Emotion Classes

The models classify facial expressions into the following categories:

- Angry 😠
- Disgust 🤢
- Fear 😨
- Happy 😄
- Sad 😢
- Surprise 😲
- Neutral 😐

---

## 🛠️ Technologies Used

| Category | Tools & Libraries |
|-----------|------------------|
| Programming Language | Python |
| Deep Learning | TensorFlow, Keras |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook |

---

## 📂 Project Structure

```text
Facial-Emotion-Recognition-Using-Deep-Learning/
│
├── 1_Perceptron.ipynb
├── 2_MLP_Backprop.ipynb
├── 3_CNN_Image_Emotion.ipynb
├── 4_VGG16_Transfer_Learning.ipynb
├── 5_Final_Comparison.ipynb
│
├── README.md
└── Dataset/
```

---

## 🚀 Model Pipeline

### 1️⃣ Perceptron Model
- Basic neural network implementation
- Single-layer architecture
- Baseline performance evaluation

### 2️⃣ Multi-Layer Perceptron (MLP)
- Backpropagation algorithm
- Hidden layers for complex feature learning
- Improved classification capability

### 3️⃣ Convolutional Neural Network (CNN)
- Automatic feature extraction
- Convolution and pooling layers
- Better spatial pattern recognition

### 4️⃣ VGG16 Transfer Learning
- Pre-trained VGG16 architecture
- Fine-tuning for emotion recognition
- Reduced training time
- Highest accuracy among all models

### 5️⃣ Final Model Comparison
- Accuracy comparison
- Loss comparison
- Performance visualization
- Model selection

---

## 📊 Workflow

```text
Facial Image Dataset
          │
          ▼
Image Preprocessing
(Resize, Normalize)
          │
          ▼
Train/Test Split
          │
          ▼
Model Training
│
├── Perceptron
├── MLP
├── CNN
└── VGG16
          │
          ▼
Model Evaluation
          │
          ▼
Performance Comparison
          │
          ▼
Emotion Prediction
```

---

## 🔍 Image Preprocessing

The following preprocessing steps were applied:

- Image Resizing
- Normalization
- Label Encoding
- Train-Test Splitting
- Data Augmentation (for deep learning models)

---

## 📈 Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Training Loss
- Validation Loss

---

## 🏆 Results

### Model Performance Comparison

| Model | Description |
|---------|------------|
| Perceptron | Baseline Model |
| MLP | Improved Feature Learning |
| CNN | Strong Spatial Feature Extraction |
| VGG16 | Best Overall Performance |

### Key Findings

- CNN significantly outperformed traditional neural networks.
- Transfer Learning with VGG16 achieved the highest accuracy.
- Pre-trained models reduced training time while improving performance.
- Deep learning architectures were more effective in capturing facial features.

---

## 📸 Sample Applications

- Smart Attendance Systems
- Human-Computer Interaction
- Mental Health Monitoring
- Customer Sentiment Analysis
- Driver Monitoring Systems
- Security and Surveillance
- Emotion-Aware Chatbots

---

## 🔮 Future Enhancements

- Real-Time Emotion Detection using OpenCV
- Webcam-Based Emotion Recognition
- Mobile Application Deployment
- Integration with Streamlit Dashboard
- Support for Video Emotion Analysis
- Ensemble Deep Learning Models

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Facial-Emotion-Recognition-Using-Deep-Learning.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open notebooks in the following order:

```text
1_Perceptron.ipynb
2_MLP_Backprop.ipynb
3_CNN_Image_Emotion.ipynb
4_VGG16_Transfer_Learning.ipynb
5_Final_Comparison.ipynb
```

---

## 📚 Dataset

This project uses a facial emotion image dataset containing labeled facial expressions from seven emotion categories.

> Note: Dataset is not included in this repository due to size limitations.

---

## 👨‍💻 Author

### Ashish Kumar Singh

- B.Tech Computer Science & Engineering
- Machine Learning & Deep Learning Enthusiast
- Python Developer

📧 Contact: kumarashish91100@gmail.com

---

## ⭐ Support

If you found this project useful, please consider:

- Starring the repository ⭐
- Forking the project 🍴
- Sharing feedback 💡

---

## 📜 License

This project is intended for educational and research purposes only.
