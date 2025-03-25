# Face-Recognition-MTCNN-FaceNet
![Result](kimdami.png)

# Overview
This project implements FaceNet and MTCNN for face recognition tasks. FaceNet is a deep learning model used to generate facial embeddings for face verification, identification, and clustering. MTCNN (Multi-task Cascaded Convolutional Networks) is employed for face detection and alignment, serving as a preprocessing step before feeding images into FaceNet.

The goal of this project is to provide a robust pipeline for face recognition, leveraging pretrained models and customizable components.

# Features
- Face Detection: Uses MTCNN to detect and align faces in images with high accuracy.
- Facial Embeddings: Generates 128D or 512D embeddings using FaceNet for downstream tasks like face comparison.
- Pretrained Models: Integrates pretrained weights for FaceNet and MTCNN.
- Modular Design: Easily adaptable for custom datasets or fine-tuning.
