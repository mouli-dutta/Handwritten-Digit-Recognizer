# Handwritten Digit Recognizer

This project is a **Handwritten Digit Recognition System** built using a **Convolutional Neural Network (CNN)** trained on the **MNIST dataset**. It also features a **real-time drawing interface** where users can draw a digit, and the trained model predicts it instantly.

## 🚀 Features
- Train a CNN model on the **MNIST dataset**.
- Perform **data visualization** and analysis.
- Save and load a trained model.
- Use **Tkinter GUI** for real-time digit drawing and prediction.
- Clear the canvas and redraw as many times as needed.

## 📌 Installation
### Prerequisites
Ensure you have Python installed along with the required libraries:
```sh
pip install numpy matplotlib seaborn tensorflow pillow opencv-python
```

### Clone the Repository
```sh
git clone https://github.com/your-username/handwritten-digit-recognizer.git
cd handwritten-digit-recognizer
```

## 🏗️ How to Run
Run the following command to start the digit recognition interface:
```sh
python handwritten_digit_recognizer.py
```
A **Tkinter GUI** will appear, allowing you to draw digits and see real-time predictions.

## 🎨 How to Use
1. **Draw a digit** on the canvas using your mouse.
2. Click **Predict** to get the model's prediction.
3. Click **Clear** to reset the canvas and draw a new digit.

## 📊 Model Training
The CNN model consists of:
- **2 Convolutional Layers** (with MaxPooling)
- **Flatten & Dense Layers**
- **Softmax Activation for Classification**

### Training Accuracy Visualization
During training, accuracy and loss graphs are plotted to evaluate performance.

## 🖼️ Example Prediction
After training, the model achieves high accuracy on handwritten digits:
![Training Graph](https://github.com/user-attachments/assets/73f64159-45c9-46e9-b99f-a188a036861b)


![Predictions](https://github.com/user-attachments/assets/734b5797-a083-4f56-9cf9-0ca2125da6bf)



