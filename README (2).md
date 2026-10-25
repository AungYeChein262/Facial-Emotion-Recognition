Facial Emotion Recognition using Transfer Learning and Test-Time
Augmentation

Project Overview This project implements a facial emotion recognition
system using deep convolutional neural networks with transfer learning.
The model is trained on the RAF-DB dataset and enhanced using Test-Time
Augmentation and Grad-CAM for interpretability.

Project Structure

Core Files - model_B.keras: Final trained model used for prediction. -
labels.json: Mapping of class indices to emotion labels.

Training - Model_B.ipynb: Contains data loading, preprocessing, model
development, training, and evaluation.

Demo / Inference - final_demo.ipynb: Used to load the
trained model and perform predictions on new images.

Dataset - dataset/: RAF-DB dataset organised into folders based on
emotion classes.

Sample Inputs - demo_input.jpg and shared_input.jpg: Example images used
for testing the model.

Requirements - Python 3.x - TensorFlow / Keras - NumPy - Matplotlib

How to Run

Train Model - Open Model_B.ipynb and run all cells.

Run Demo - Open final_demo.ipynb and run all cells to
perform predictions.

Performance 
- Accuracy without TTA: \~79.14% 
- Accuracy with TTA: \~79.86%

Additional Features 
- Transfer Learning for improved feature extraction. 
- Test-Time Augmentation for more robust predictions. 
- Grad-CAM for visual explanation of model decisions.

References 
- Based on research in transfer learning, data augmentation,
facial emotion recognition, and explainable AI.

Student Name: Aung Ye Chein
Module: CET313 Artificial Intelligence
