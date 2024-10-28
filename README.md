# Diabetic-Retinopathy-Detection-using-InceptionV3

Description:
This project applies deep learning techniques to classify diabetic retinopathy severity levels using retinal images. Using the Inception V3 model, the project predicts the presence and severity of diabetic retinopathy, supporting early detection and potential remote screening solutions.

Dataset:

Labels: Metadata with patient demographics and diabetic retinopathy (DR) severity levels.
Images: 5,164 retinal images from 1,291 diabetic patients, classified into five DR severity classes (0–4).
Methodology:

Phase 1 - Model Training: Used a pretrained Inception V3 model in TensorFlow for initial classification on the Mobile Brazilian dataset.
Phase 2 - Fine-Tuning: Enhanced model accuracy through fine-tuning and compared results with initial predictions.
Phase 3 - Model Comparison: Employed PyTorch to re-train the model and compared performance between TensorFlow and PyTorch implementations.
This project demonstrates the potential of CNNs for automated diabetic retinopathy screening, helping to make early detection more accessible and cost-effective.
