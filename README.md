# Urdu-Sign-Language-Model

Model Description

This model supports Urdu Sign Language (USL) to enable two-way communication between deaf/mute individuals and hearing people through real-time gesture recognition.

The model is trained on the UAlpha40 Urdu Sign Language Dataset:
https://data.mendeley.com/datasets/3pvnnckxyb/2

Hand keypoints were extracted from images and videos, normalized, and used as input features. The architecture combines Conv1D layers for feature extraction with BiLSTM layers for temporal sequence learning.

The trained model achieves 87.98% gesture recognition accuracy. Along with the TensorFlow Lite (.tflite) model, the extracted keypoints are also provided, enabling direct retraining and fine-tuning. The model can be easily converted to Keras / TensorFlow formats and is optimized for mobile and real-time applications.
