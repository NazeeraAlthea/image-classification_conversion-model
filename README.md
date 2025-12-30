# Image Classification and Model Conversion

This repository is a learning project focused on:
1. **Image classification using TensorFlow**
2. **Model conversion into multiple deployment formats**

The goal of this project is to understand the end-to-end workflow of training an image classification model and exporting it into different formats for various platforms.

---

## 📁 Repository Structure

- `saved_model/`  
  TensorFlow SavedModel format (default TensorFlow export)

- `tflite/`  
  TensorFlow Lite model for mobile and edge deployment

- `tfjs_model/`  
  TensorFlow.js model for web-based inference

- `notebook.ipynb`  
  Jupyter Notebook containing model training and conversion steps

- `requirements.txt`  
  Python dependencies used in this project

---

## 🧠 Project Overview

In this project, I:
1. Trained a **simple image classification model**
2. Exported the trained model into three formats:
   - **TensorFlow SavedModel**
   - **TensorFlow Lite (TFLite)**
   - **TensorFlow.js (TFJS)**

The exported model folders are included as proof that the conversion process was successfully completed.

---

## 🚀 How to Run

1. Clone this repository
```bash
git clone https://github.com/NazeeraAlthea/image-classification_conversion-model
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Open `notebook.ipynb` using Jupyter Notebook or Google Colab to explore:
   - Model training
   - Model export and conversion steps

---

## 🛠 Technologies Used

- Python
- TensorFlow
- TensorFlow Lite
- TensorFlow.js

---

## 📌 Notes

- The dataset is not included in this repository.
- The focus of this project is learning model conversion workflows rather than achieving high accuracy.
- Exported models can be used directly for inference in their respective environments.

---

## 📄 License

This project is open source and intended for educational purposes.
