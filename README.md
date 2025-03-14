# PlantDiseaseDetection
Training for classification of different plant diseases

Dataset is taken from kaggle : 
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset
## 📌 Project Overview
This project aims to develop an AI-powered **Plant Disease Detection System** that classifies plant diseases using deep learning techniques. The system helps farmers detect diseases early, reducing crop losses and promoting sustainable agricultural practices.

## 🚀 Features
- **Deep Learning Model** trained using Convolutional Neural Networks (CNN)
- **Real-time Disease Prediction** using a web-based interface
- **User-friendly Application** built with Streamlit
- **Supports Multiple Crop Diseases** based on the PlantVillage dataset
- **Helps in Early Disease Detection** to improve agricultural productivity

## 📂 Project Structure
```
📦 Plant-Disease-Detection
├── 📜 PlantDiseaseDetection.ipynb  # Jupyter Notebook for model training
├── 📜 app.py  # Streamlit app for disease detection
├── 📜 requirements.txt  # Required dependencies
├── 📂 model  # Trained model files
├── 📂 images  # Sample images for testing
└── 📜 README.md  # Project documentation
```

## 🛠️ Tools and Technologies Used
- **Programming Language:** Python
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy, PIL
- **Framework:** Streamlit (for web deployment)
- **Dataset:** PlantVillage dataset

## 📊 How It Works
1. Upload a plant leaf image in the **Disease Recognition** section.
2. The model analyzes the image and predicts the disease category.
3. The system displays the **disease name** along with a confidence score.
4. Farmers can take corrective action based on the predictions.

## 📌 Future Enhancements
- **Edge Computing:** Deploying the model on mobile devices for offline predictions.
- **Disease Severity Estimation:** Predicting the severity of the infection for better decision-making.
- **Automated Treatment Suggestions:** Providing recommendations based on detected diseases.
