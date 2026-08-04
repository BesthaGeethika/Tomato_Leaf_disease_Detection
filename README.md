# 🍅 Tomato Leaf Disease Detection using Deep Learning

An AI-powered web application that detects diseases in tomato leaves using a Convolutional Neural Network (CNN). The application allows users to upload an image of a tomato leaf and predicts whether it is healthy or affected by a disease.

---

## 📌 Project Overview

Tomato crops are highly susceptible to various leaf diseases that can significantly reduce crop yield. This project leverages Deep Learning to automatically identify diseases from tomato leaf images, helping farmers and researchers take timely preventive measures.

The application is built using **TensorFlow/Keras** for model training and **Streamlit** for the user interface.

---

## ✨ Features

- Upload tomato leaf images
- Detect healthy and diseased leaves
- Deep Learning-based image classification
- User-friendly Streamlit interface
- Fast and accurate predictions
- Pre-trained Keras model included

---

## 🖼️ Supported Classes

The model can classify tomato leaves into the following categories:

- 🍃 Healthy
- 🍂 Bacterial Spot
- 🍂 Early Blight
- 🍂 Late Blight
- 🍂 Leaf Mold
- 🍂 Septoria Leaf Spot
- 🍂 Spider Mites
- 🍂 Target Spot
- 🍂 Mosaic Virus
- 🍂 Yellow Leaf Curl Virus

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| TensorFlow / Keras | Deep Learning |
| NumPy | Numerical Operations |
| OpenCV | Image Processing |
| Matplotlib | Visualization |
| Streamlit | Web Application |
| Jupyter Notebook | Model Development |

---

## 📂 Project Structure

```
Tomato_Leaf_disease_Detection/
│
├── Train/
├── Valid/
├── trained_model.keras
├── training_hist.json
├── train_disease.ipynb
├── test_disease.ipynb
├── main.py
├── home_page.jpeg
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/BesthaGeethika/Tomato_Leaf_disease_Detection.git
```

```bash
cd Tomato_Leaf_disease_Detection
```

---

### Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run main.py
```

The application will open automatically in your browser.

---

## 📷 How to Use

1. Launch the Streamlit application.
2. Upload an image of a tomato leaf.
3. Click **Predict**.
4. View the predicted disease class.

---

## 🧠 Model Information

- Framework: TensorFlow/Keras
- Model File: `trained_model.keras`
- Image Classification using CNN
- Multi-class Classification

---

## 📊 Dataset

The model is trained using a Tomato Leaf Disease dataset containing images of healthy and diseased tomato leaves.

Typical classes include:

- Healthy
- Bacterial Spot
- Early Blight
- Late Blight
- Leaf Mold
- Septoria Leaf Spot
- Spider Mites
- Target Spot
- Mosaic Virus
- Yellow Leaf Curl Virus

---

## 📈 Future Enhancements

- Mobile Application
- Real-time Camera Detection
- Disease Severity Estimation
- Fertilizer Recommendation
- Treatment Suggestions
- Cloud Deployment
- Multi-Crop Disease Detection

---

## 👩‍💻 Author

**Geethika Bestha**

Integrated M.Tech - Computer Science and Engineering

VIT University, Vellore

GitHub: https://github.com/BesthaGeethika

---

## 📜 License

This project is intended for educational and research purposes.

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
