# 🤟 Sign Language Recognition using CNN

A deep learning project that recognizes American Sign Language (ASL) hand gestures using a Convolutional Neural Network (CNN) trained on the Sign Language MNIST dataset.

## 📌 Project Overview

This project uses a CNN model built with TensorFlow/Keras to classify hand sign images into different ASL alphabet classes. The model is trained on grayscale images (28×28 pixels) and can be used as the foundation for real-time hand sign recognition applications.

---

## 📂 Dataset

**Dataset:** Sign Language MNIST

- Training Set: `sign_mnist_train.csv`
- Testing Set: `sign_mnist_test.csv`

Each sample contains:

- Label (class)
- 784 pixel values (28 × 28 grayscale image)

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Google Colab

---

## 🧠 Model Architecture

The model consists of:

- Convolutional Layers (Conv2D)
- MaxPooling Layers
- Dropout Layers
- Flatten Layer
- Fully Connected (Dense) Layers
- Softmax Output Layer

Training optimization:

- Early Stopping
- Adam Optimizer
- Categorical Crossentropy Loss

---

## 📊 Model Performance

- **Test Accuracy:** **94.67%**
- **Test Loss:** **0.26**

The model achieves high classification accuracy while maintaining low validation loss.

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-mohamedelashery18/sign-language-recognition.git
```

2. Install dependencies

```bash
pip install tensorflow numpy pandas matplotlib
```

3. Download the dataset from Kaggle.

4. Place the CSV files in the project directory.

5. Run the notebook:

```
hand_sign_detection_proj.ipynb
```

---

## 📁 Project Structure

```
├── hand_sign_detection_proj.ipynb
├── model_hand_sign.keras
├── sign_mnist_train.csv
├── sign_mnist_test.csv
├── README.md
```

---

## 📈 Future Improvements

- Real-time webcam prediction using OpenCV.
- MediaPipe hand detection.
- Support all ASL alphabet letters.
- Model deployment using Streamlit or Flask.
- Mobile application integration.

---

## 👨‍💻 Author

**Mohamed Elashry**

Artificial Intelligence Graduate

Interested in:
- Data Analysis
- Machine Learning
---

## 📜 License

This project is for educational and research purposes.
