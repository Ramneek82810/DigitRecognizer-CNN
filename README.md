# 🔢 Digit Recognizer using CNN

A Convolutional Neural Network (CNN) based image classification project that recognizes handwritten digits (0–9) using the MNIST dataset. This project demonstrates a fundamental deep learning workflow including data preprocessing, model training, and evaluation.

## 🚀 Features

- 🧠 Built using Convolutional Neural Networks (CNN)  
- 🔢 Recognizes digits from 0 to 9 using MNIST dataset  
- 📉 Shows training and validation accuracy and loss  
- 🖼️ Visualizes predictions and confusion matrix  
- ✅ Lightweight and beginner-friendly  

## 📁 Project Structure

```
DigitRecognizer-CNN/
│
├── handwriting.py               
├── recognition.py              
├── assets/fonts
├── model.h5              
└── README.md               
```

## ⚙️ Installation

### 1. Clone the Repository

```
git clone https://github.com/Ramneek82810/DigitRecognizer-CNN.git
cd DigitRecognizer-CNN
```

### 2. Create and Activate Virtual Environment (optional but recommended)

```
python -m venv .venv
source .venv/bin/activate    # On Windows use: .venv\Scripts\activate
```

### 3. Install Dependencies

```
pip install tensorflow keras numpy matplotlib seaborn
```


## 💡 How It Works

- Loads and preprocesses the MNIST dataset  
- Trains a CNN to classify digits based on pixel patterns  
- Evaluates model performance using test accuracy and confusion matrix  
- Visualizes results using matplotlib and seaborn  

## 📌 Todo

- Add support for custom digit image uploads  
- Implement GUI using Streamlit or Tkinter  
- Save and load trained models for reuse  
- Explore advanced architectures (ResNet, MobileNet, etc.)  

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.


