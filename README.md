# 🧠 CV Object Detection & Classification from Scratch

This project is a complete end-to-end pipeline for object detection and classification using classic computer vision techniques, HOG features, and neural networks. It even includes a user interface using Gradio for real-time testing.

## 📌 Features

- 🔄 Preprocessing (resizing, grayscaling)
- ✂️ Segmentation (thresholding, edge detection with Canny)
- 🔍 Feature Extraction using HOG (Histogram of Oriented Gradients)
- 🧠 Classification using a Neural Network (Keras Sequential model)
- 📊 Evaluation using accuracy, precision, recall, F1-score, and confusion matrix
- 🖼️ Simple Web Interface built with Gradio

## 📁 File Structure

- `cv_Project.ipynb` — Main notebook with the full pipeline
- `requirements.txt` — All required Python packages
- `images/` — (Optional) Directory to add input test images
- `README.md` — Project documentation

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cv-object-detection.git
   cd cv-object-detection
   ```
Install dependencies:

pip install -r requirements.txt
Run the notebook:


jupyter notebook cv_Project.ipynb
Run the Gradio Interface (last cell in notebook) and upload your own images!

