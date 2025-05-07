# 🔍 Recognizing Handwritten Digits with Deep Learning – Smarter AI Application

A deep learning-based AI system to accurately recognize handwritten digits using neural networks. This project demonstrates the power of AI in interpreting human handwriting, a key application in OCR (Optical Character Recognition), smart document processing, and more.

## 🧠 Project Highlights

- **Dataset**: MNIST handwritten digits dataset (60,000 training & 10,000 test images).
- **Model**: Convolutional Neural Network (CNN) built using TensorFlow/Keras.
- **Accuracy**: Achieves >98% accuracy on test data.
- **Application**: Can be extended to real-world handwriting recognition tasks.

## 🚀 Technologies Used

- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- Matplotlib / Seaborn (for visualization)  
- Jupyter Notebook  

## 📁 Project Structure

```
📦 Handwritten-Digit-Recognizer
 ┣ 📂 data/
 ┣ 📂 models/
 ┣ 📂 notebooks/
 ┣ 📂 examples/
 ┣ 📜 main.py
 ┣ 📜 requirements.txt
 ┗ 📜 README.md
```

## 🧪 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/handwritten-digit-recognizer.git
   cd handwritten-digit-recognizer
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the model**
   ```bash
   python main.py
   ```

## 📊 Sample Results

| Input Image | Predicted Digit |
|-------------|------------------|
| ![img1](examples/digit_3.png) | 3 |
| ![img2](examples/digit_7.png) | 7 |

## 📌 Future Work

- Extend to letters (EMNIST dataset)
- Integrate with mobile/web application
- Add GUI for real-time drawing and prediction
