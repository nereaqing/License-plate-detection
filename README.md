# License-plate-detection
This repository contains code and resources for a license plate detection and recognition project. The project encompasses two distinct approaches: classical computer vision and deep learning. It has been fine-tuned a pre-trained model and implemented a YOLO (You Only Look Once) model for license plate detection, and has been used EasyOCR library for content recognition.

## Project Overview
License plate detection and recognition play a crucial role in various applications, from traffic management to security and surveillance. This project aims to provide efficient solutions for detecting license plates in images and extracting their content. The repository presents two distinct methods.

### Classical Computer Vision
In the classical computer vision approach, it is leveraged traditional image processing techniques, including edge detection, contour analysis, and character recognition. 
*See in Classical computer vision.ipynb*

### Deep Learning
The deep learning approach explores the power of neural networks for license plate detection and recognition. Two primary methods are employed:

- **Fine-tuning a Pre-trained Model**: We take a pre-trained deep learning model, adapt it to our license plate dataset, and fine-tune it for improved accuracy. *See in Pre trained model.ipynb*

- **YOLO (You Only Look Once) Model**: We implement YOLO, a real-time object detection system, to identify license plates. *See in yolo.ipynb*. All the results, metrics and qualitative results are in the folder *runs/detect/train9*

## Collaborators
- Júlia Garcia Torné
- Guillem Samper Argelagués
- Nerea Qing Muñoz Martin
