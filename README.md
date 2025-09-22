# MNIST Digit Classification (CNN)

This project implements a Convolutional Neural Network (CNN) using **Keras** to classify handwritten digits from the [MNIST dataset](http://yann.lecun.com/exdb/mnist/).  
The model is trained to recognize digits (0–9) from 28x28 grayscale images and can also predict custom digit images provided by the user.

---

## 🚀 Features
- Loads and preprocesses the MNIST dataset
- Normalizes and reshapes the images for CNN input
- Builds a CNN model with:
  - Convolutional layers
  - MaxPooling layers
  - Dense (Fully Connected) layers
- Trains the model using categorical cross-entropy loss
- Evaluates performance on test data
- Makes predictions on:
  - Test dataset images
  - Custom images (PNG/JPG)

---

## 🛠️ Requirements
Install dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```
## 📂 Project Structure
```bash
mnist-cnn/
│── mnist_cnn.py
│── requirements.txt   
│── README.md          
└── testing_images/ 
```



## ▶️ Usage
1. Clone the repository:

```bash
git clone https://github.com/Abdullah0Aslam/MNIST-CNN-Project.git
cd MNIST-CNN-Project

```
2. Train the model:
```bash
python MNIST-CNN-Project.py

```

3. The script will:
- Train the CNN for 10 epochs

- Display random test predictions with images

- Predict custom digit images from testing_images/
## 📊 Model Summary
- Input: (28, 28, 1) grayscale image

- Conv2D + MaxPooling layers for feature extraction

- Dense layers with ReLU activation

- Output layer with Softmax (10 classes)
## 📷 Example Output
- True vs Predicted labels shown with images

- Custom image prediction example:

```yaml
Predicted Digit: 1
```
## 🚀 Technologies Used

- Python

- NumPy

- Matplotlib

- keras

- cv2



## 🤝 Contribution

Contributions are welcome!

- Fork this repository

- Create a new branch - (feature-branch)

- Commit your changes

- Open a Pull Request

