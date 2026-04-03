# 🚗 Car Damage Detection using Deep Learning (CNN)

**📌 Overview**

This project builds a deep learning-based Car Damage Detection system that classifies vehicle images into multiple damage categories using a Convolutional Neural Network (ResNet50).
The system is deployed using a Streamlit web application, allowing users to upload car images and get instant damage classification.

**🎯 Problem Statement**
Manual inspection of car damage is:

Time-consuming
Subjective
Not scalable

This project solves the problem by automating damage detection using computer vision and deep learning.

**🧠 Solution Approach**
The system follows a real-world deep learning pipeline:

- Image preprocessing and normalization
- Transfer learning using ResNet50
- Fine-tuning deeper layers for improved accuracy
- Classification into predefined damage categories
- 
**📊 Damage Categories**
Front Normal
Front Breakage
Front Crushed
Rear Normal
Rear Breakage
Rear Crushed

**⚙️ Tech Stack**
Python
PyTorch
Torchvision
Streamlit
Pillow

**🤖 Model Details**

Base Model: ResNet50 (Pretrained)
Transfer Learning: Enabled
Fine-tuning: Last layers unfrozen
Regularization: Dropout layer
Image Size: 224 × 224

**📈 Output**
Predicted damage category for the uploaded image

**🖥️ Web Application**
The Streamlit app allows users to:
- Upload a car image
- Process the image through the trained model
- Get instant classification results
  
**🚀 How to Run Locally**
git clone https://github.com/<your-username>/car-damage-detection-cnn.git
cd car-damage-detection-cnn
pip install -r requirements.txt
streamlit run app.py

**📁 Project Structure**
car-damage-detection-cnn/
│
├── app.py
├── model_helper.py
├── requirements.txt
├── README.md
│
├── artifacts/
│   └── saved_model.pth
│
├── notebooks/
│   ├── damage_prediction.ipynb
│   └── hyperparameter_tuning.ipynb

**💡 Business Impact**
- Enables automated vehicle inspection
- Reduces manual assessment effort
- Speeds up insurance claim processing
- Scalable for real-world deployment
  
**🔥 Key Highlights**
Deep Learning (CNN + Transfer Learning)
Real-world computer vision application
End-to-end pipeline (image → prediction → UI)
Practical deployment using Streamlit

**🔮 Future Improvements**
Use object detection (YOLO) for damage localization
Support multi-image analysis
Deploy as a web/mobile application
Improve dataset and model accuracy

**📌 Summary**
This project demonstrates how deep learning and computer vision can be applied to automate real-world problems like vehicle damage assessment, improving efficiency and scalability.
