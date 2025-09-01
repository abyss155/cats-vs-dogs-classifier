# 🐱🐶 Cats vs Dogs Classifier

A Convolutional Neural Network (CNN) built using **TensorFlow & Keras** to classify images as either **Cat** or **Dog**.

## 📌 Project Workflow
1. Data preprocessing (resize 128x128, normalize, split train/validation)
2. CNN Model (Conv → ReLU → Pool → Conv → ReLU → Pool → Flatten → Dense → Sigmoid)
3. Training (10–15 epochs) with accuracy/loss plots
4. Evaluation on validation set
5. Random image predictions
6. Model saved & reloaded

## 📊 Results
- Training Accuracy: ~XX%
- Validation Accuracy: ~XX%
- Example Predictions:

![Sample Results](images/sample_results.png)

## 🚀 Tech Stack
- TensorFlow / Keras
- NumPy, Matplotlib, Pillow
- Scikit-learn

## 📂 Files
- `DL_Assignment_Dog_vs_Cat_Classifier.ipynb` → Notebook with code
- `requirements.txt` → Dependencies
- `model/` → Saved trained model (`.keras`)
- `images/` → Example results

