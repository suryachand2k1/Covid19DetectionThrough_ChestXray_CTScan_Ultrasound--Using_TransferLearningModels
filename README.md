# Machine Learning Model for COVID-19 Detection from Medical Images

## Project Overview
This project utilizes advanced machine learning techniques to detect COVID-19 from various medical images like Chest X-rays, CT Scans, and Ultrasounds.

## Workflow
1. **Importing Packages:** Import TensorFlow, OpenCV, and other necessary libraries.
2. **Image Exploration & Preprocessing:** Includes conversion, feature extraction, and preparation for model training.
3. **Model Training & Selection:** Utilize models like VGG16, VGG19, Xception, Inception ResNet, Inception V3, DenseNet, and ResNetv2 for training.
4. **Model Deployment:** Deploy using Flask Framework for real-time predictions.
5. **Prediction Process:** Upload and preprocess images with the trained model to generate COVID-19 predictions.

## Technical Aspects
- Deep Learning models like VGG16, VGG19, and others are used for their ability to recognize complex patterns in medical images.
- TensorFlow and OpenCV are crucial for image processing and model implementation.
- The model's accuracy and efficiency are paramount for reliable COVID-19 detection.
- Flask is used for deploying the model in a web application, enabling real-time interaction and prediction.

## How to Run
- Use Google Colab with GPU runtime for training the model using Transfer Learning.
- Save the built model to the application folder and update the model path in `app.py`.
- Note: Building your model is recommended for better validation accuracy.
- Pre-built model files can be downloaded from:
  - Chest X-rays: [Download](https://drive.google.com/file/d/171Y-uGmgE1hNL4ih9aCOb2mOgDq7wu1i/view?usp=sharing)
  - CT Scans: [Download](https://drive.google.com/file/d/1-AvZAULr7BRDtQ0FOLMf3vLs40klUq6-/view?usp=sharing)
  - Ultrasounds: [Download](https://drive.google.com/file/d/1-FRgHuSZUyUZCFGVSVz4dfBRR7czb2_v/view?usp=sharing)

## Technologies Used
- Python, Flask, TensorFlow, OpenCV, and deep learning architectures.


