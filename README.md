# 🧠 Handwritten Digit Classification using CNN (MNIST)

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** to classify handwritten digits (0–9) using the **MNIST dataset**.

It compares the performance of:

* ✅ A **Complex CNN Model** (deep architecture with regularization)
* ✅ A **Simple CNN Model** (lightweight baseline)

The project demonstrates **deep learning, model optimization, and performance evaluation techniques**.

---

## 🚀 Features

* 📊 Data preprocessing and normalization
* 🔄 Data augmentation for improved generalization
* 🧠 Two CNN architectures (Simple vs Complex)
* 📉 Training optimization using:

  * Early Stopping
  * Reduce Learning Rate
* 📈 Performance visualization:

  * Accuracy & Loss graphs
  * Confusion Matrix
  * Precision, Recall, F1-score
* 📊 Model comparison
* 🔍 Prediction visualization on test data
* 🧾 Model architecture flowchart generation

---

## 🛠️ Tech Stack

* **Python**
* **TensorFlow / Keras**
* **NumPy, Pandas**
* **Matplotlib, Seaborn**
* **Scikit-learn**

---

## 📂 Project Structure

```
├── main.py
├── complex_model_flowchart.png
├── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install dependencies

```bash
pip install numpy pandas tensorflow matplotlib seaborn scikit-learn
```

---

## ▶️ Usage

Run the script:

```bash
python main.py
```

---

## 🧠 Model Architectures

### 🔹 Complex CNN

* Multiple Conv2D + BatchNorm layers
* MaxPooling & Dropout for regularization
* Dense layers for classification

### 🔹 Simple CNN

* Basic Conv2D + Pooling
* Lightweight and faster training

---

## 📊 Results & Evaluation

### 📈 Metrics Used

* Accuracy
* Loss
* Confusion Matrix
* Precision, Recall, F1-Score

### 🏆 Key Observations

* Complex model achieves **higher accuracy**
* Better generalization due to:

  * Data augmentation
  * Batch normalization
  * Dropout

---

## 📸 Output Samples

### 📊 Training Graphs

(Add screenshot here)

### 🔢 Confusion Matrix

(Add screenshot here)

### 🎯 Predictions

(Add screenshot here)

---

## 📉 Model Comparison

| Model       | Accuracy |
| ----------- | -------- |
| Complex CNN | ~99%     |
| Simple CNN  | ~97-98%  |

---

## 💡 Key Learnings

* Deep CNNs outperform shallow models in image tasks
* Regularization prevents overfitting
* Data augmentation improves robustness
* Visualization helps in model evaluation

---

## 🔮 Future Improvements

* 🚀 Deploy as a web app (Flask/Streamlit)
* 📦 Export model for real-time predictions
* 🧠 Try advanced architectures (ResNet, EfficientNet)
* 📱 Build mobile integration

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 🙌 Acknowledgements

* MNIST Dataset (TensorFlow/Keras)
* Deep Learning community

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

---
