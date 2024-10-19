# Diabetic Retinopathy Classification Using InceptionV3  

Welcome to the **Diabetic Retinopathy Classification** repository! This project leverages **PyTorch** and the **InceptionV3** architecture to build a machine learning model for detecting diabetic retinopathy (DR) from retinal images. The dataset is sourced from **Google Drive**, and the model is trained and evaluated with detailed performance metrics such as accuracy, confusion matrix, and sensitivity/specificity scores.  

## Table of Contents  
- [Project Overview](#project-overview)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Training and Validation](#training-and-validation)  
- [Model Performance](#model-performance)  
- [Results](#results)  
- [Acknowledgements](#acknowledgements)  

---

## Project Overview  
This repository contains a **deep learning-based classification model** to detect diabetic retinopathy, trained using the **InceptionV3** architecture. The model goes through preprocessing, splitting the dataset into **training, validation, and test sets**. The training process is tracked over 15 epochs using **tqdm progress bars**, with evaluation metrics displayed throughout to assess the model's accuracy and predictive quality.  

---

## Features  
- **InceptionV3 Architecture**: A pretrained model tailored for medical image classification.  
- **Performance Metrics**: Includes confusion matrix, classification reports, and accuracy.  
- **Specificity and Sensitivity** Calculation for a comprehensive view of performance.  
- **Visualization**: Confusion matrix visualization to interpret the results better.  
- **Training with CUDA Support**: Optimized for both CPU and GPU environments.  

---

## Installation  
To run this project, follow these steps:  

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/yourusername/diabetic-retinopathy-classification.git  
   cd diabetic-retinopathy-classification  
