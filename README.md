# Organic and Recyclable Waste Classifier

A deep learning project to classify waste images into two categories: **organic** and **recyclable**. This classification can help improve automated waste segregation systems for a more sustainable environment.

## 📁 Project Structure

- `Organic-and-Recyclable-waste-classifier.ipynb`: Jupyter Notebook containing the entire pipeline from data loading, preprocessing, model training, evaluation, and predictions.
- `README.md`: Project overview and instructions (you are here).

## 🧠 Model

The classifier is built using a Convolutional Neural Network (CNN) in TensorFlow/Keras. It includes:

- Data preprocessing and augmentation
- CNN architecture with multiple convolutional and pooling layers
- Model evaluation using accuracy and loss metrics
- Image predictions with visualization

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Recommended packages:
  ```bash
  pip install tensorflow matplotlib numpy opencv-python
  ```

### Run the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/shivangi4880/Smart-Waste-Management.git
   cd organic-recyclable-classifier
   ```

2. Launch the notebook:
   ```bash
   jupyter notebook Organic-and-Recyclable-waste-classifier.ipynb
   ```

3. Follow the cells step-by-step to train or evaluate the model.

## 📊 Results

The notebook shows training and validation accuracy/loss, and provides visual predictions on test images.
![image](https://github.com/user-attachments/assets/12106df2-ea78-4c34-a868-9c9cfed71361)
Training and Validation accuracy 
Final Training Accuracy - 92.85%
Final Validation Accuracy - 90.77%

![image](https://github.com/user-attachments/assets/69250638-8e58-4d06-9d46-1c618857a77d)
Training and Validation loss
Final Training Loss - 18.78%
Final Validation Accuracy - 26.97%

## 📸 Sample Predictions

![image](https://github.com/user-attachments/assets/7f575ed6-f4a1-4689-a358-9b0096b75d96)


## 📂 Dataset

The dataset should contain images divided into two folders:
```
dataset/
├── TEST/
    └── O/
    └── R/
└── TRAIN/
    └── O/
    └── R/
```

You can download the dataset from the original Kaggle notebook:

🔗 [Waste Classification with CNN by beyzanks](https://www.kaggle.com/code/beyzanks/waste-classification-with-cnn)


## 🔧 Future Improvements

- Add a web interface using Streamlit or Flask.
- Train on larger, real-world waste datasets.
- Improve classification accuracy with transfer learning.
