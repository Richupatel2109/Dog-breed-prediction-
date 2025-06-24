# Dog-breed-prediction-

## 📄 requirements.txt
```bash
numpy
matplotlib
pandas
seaborn
scikit-learn
tensorflow
keras
opencv-python
```
---
# 🐶 Dog Breed Prediction using CNN

This project uses Convolutional Neural Networks (CNN) to classify dog breeds from images. The notebook walks through the full pipeline — from data preprocessing and augmentation to model training and evaluation using TensorFlow and Keras.

---

## 📁 Project Structure
### 🔧 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/dog-breed-prediction.git
   cd dog-breed-prediction
   ```

2. **Create a virtual environment**
```bash
python3 -m venv venv
source venv/bin/activate   
# On Windows: venv\Scripts\activate
```
3. **Install dependencies**
```bash
pip install -r requirements.txt
```
4. **Download the dataset**

    You can use the Stanford Dogs Dataset or Kaggle’s Dog Breed Identification.
    Place the data in the data/ directory.
---
## 📊 Model Overview

  Architecture: Convolutional Neural Network (CNN) with multiple Conv2D and MaxPooling layers.
  Optimizer: Adam
  Loss Function: Categorical Crossentropy
  Metrics: Accuracy
  Libraries: TensorFlow, Keras, OpenCV
---
## 🧪 Results

The model achieves decent accuracy in classifying various dog breeds. Sample predictions are stored in the images/ directory.

