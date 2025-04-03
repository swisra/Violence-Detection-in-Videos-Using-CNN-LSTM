# Violence-Detection-in-Videos-Using-CNN-LSTM
## Project Overview  
This project aims to develop an AI-based system for detecting violent activities in videos using a combination of Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks. The system is designed to analyze video frames, extract spatial and temporal features, and classify whether a scene contains violent actions.


##  Technologies Used  
**MobileNet (CNN)** – for spatial feature extraction  
**LSTM** – for temporal sequence learning  
**TensorFlow & Keras** – deep learning framework  
**OpenCV** – for video processing  
**Google Colab** – for model training  
**VS Code** – for implementation & testing  



##  How It Works  
**1-Feature Extraction** : MobileNet extracts key features from each video frame.  
**2-Temporal Analysis** : LSTM captures motion patterns over sequential frames.  
**3-Prediction** : The model classifies each scene as **violent or non-violent**.  



##  Dataset & Training  
The dataset is a combination of:  
- **Multiple online video sources**  
- **Self-recorded videos** (Sony A7 camera) with various angles & lighting conditions  

**Training Process:**  
- Performed on **Google Colab** with **transfer learning**.  
- Optimized using **Adam optimizer** and evaluated with **Accuracy, Precision, Recall, and F1-score**.  



##  Model Evaluation  
**Metrics Used:**  
**Accuracy** – measures overall performance  
**Precision & Recall** – evaluates false positives & false negatives  
**F1-score** – balances precision & recall  

**Testing Scenarios:**  
**Real-time video processing**  
**Frame-by-frame analysis**  



##  Challenges & Future Work  
   **Challenges Faced:**  
- **Dataset preprocessing & augmentation**  
- **TensorFlow Lite compatibility for embedded deployment**  
- **Performance optimization for real-time detection**  

**Future Enhancements:**  
Deploying on **Raspberry Pi** for edge surveillance applications  

---

 This project aims to improve **public safety** by enabling real-time AI-powered violence detection in videos.  
