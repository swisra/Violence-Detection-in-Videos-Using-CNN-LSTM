# Violence-Detection-in-Videos-Using-CNN-LSTM
This project aims to develop an AI-based system for detecting violent activities in videos using a combination of Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks. The system is designed to analyze video frames, extract spatial and temporal features, and classify whether a scene contains violent actions.

Approach:
Feature Extraction with CNN (MobileNet):

A pre-trained MobileNet model is used for efficient feature extraction from video frames.

MobileNet is chosen due to its lightweight architecture, making it suitable for real-time applications and embedded systems.

Temporal Analysis with LSTM:

Extracted features from sequential frames are fed into an LSTM network to capture motion patterns and detect violent activities.

LSTM is used to process the temporal dependencies between frames, enhancing the system’s accuracy in distinguishing violence from normal actions.

Dataset and Training:

The model is trained using a dataset comprising multiple online sources and self-recorded videos.

Training is performed on Google Colab using transfer learning for the CNN and fine-tuning the LSTM.

Implementation & Evaluation:

The trained model is tested for real-time and per-frame violence detection in videos using VS Code.

Various evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess model performance.

Challenges & Deployment:

Initial challenges included dataset preprocessing, TensorFlow Lite compatibility for embedded deployment, and real-time performance optimization.

Future work includes deploying the model on Raspberry Pi or edge devices for surveillance applications.
