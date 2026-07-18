# 👁️ Retinal OCT Image Classification with Deep Learning

An AI-powered web application for automatic retinal disease classification using **Optical Coherence Tomography (OCT)** images and **DenseNet121**.

The system assists ophthalmologists by providing fast, reliable, and accurate retinal disease predictions from OCT scans.

---

## 📷 Project Preview

### 🏠 Home Page

![Home Page](images/home.png)

---

### 📄 About Page

![About Page](images/about.png)

---

### 🔍 Prediction Page

![Prediction](images/prediction.png)

---

## 📌 Overview

Retinal diseases are among the leading causes of blindness worldwide. Early diagnosis is essential for preserving vision.

This project leverages **DenseNet121** with Transfer Learning to automatically classify retinal OCT images into **eight disease categories**, providing an intelligent clinical decision support system.

---

# ✨ Features

- AI-powered retinal disease classification
- DenseNet121 Transfer Learning
- OCT image preprocessing
- Data augmentation
- Flask REST API
- React + Vite frontend
- Fast and accurate prediction
- Responsive web interface

---

# 🩺 Supported Diseases

- AMD
- CNV
- DME
- Drusen
- ERM
- MH (Macular Hole)
- RVO
- Normal

---

# 🧠 Model

**Architecture**

DenseNet121 (Transfer Learning)

### Training Strategy

- Freeze backbone
- Train classifier
- Fine-tune Dense Blocks
- Early Stopping
- Learning Rate Scheduling

---

# ⚙️ Training Configuration

| Parameter | Value |
|-----------|-------|
| Image Size | 224 × 224 |
| Batch Size | 32 |
| Optimizer | AdamW |
| Loss Function | CrossEntropyLoss |
| Scheduler | ReduceLROnPlateau |
| Epochs | 10 |

---

# 📈 Results

| Metric | Score |
|---------|-------|
| Training Accuracy | **95.63%** |
| Validation Accuracy | **95.21%** |
| Test Accuracy | **95.21%** |

---

# 🛠️ Tech Stack

### AI

- Python
- PyTorch
- DenseNet121
- NumPy
- Pillow

### Backend

- Flask
- Flask-CORS

### Frontend

- React
- Vite
- Axios
- React Router

---

# 📂 Project Structure

```
Retinal-OCT-Image-Classification-With-Deep-Learning
│
├── Backend
├── Frontend
├── images
│   ├── home.png
│   ├── about.png
│   └── prediction.png
├── OCT.ipynb
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Mohamed56e/Retinal-OCT-Image-Classification-With-Deep-Learning.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Backend

```bash
python app.py
```

Run Frontend

```bash
npm install
npm run dev
```

---

# 🔄 Workflow

1. Upload an OCT retinal image.
2. Image preprocessing.
3. DenseNet121 performs inference.
4. Disease prediction.
5. Display prediction and confidence score.

---

# 🎯 Future Improvements

- Cloud deployment
- Batch image prediction
- Better UI/UX
- Hospital integration
- Patient prediction history

---

# 👨‍💻 Author

**Mohamed Esmail**

Faculty of Artificial Intelligence  
Delta University for Science and Technology

---

# ⭐ Support

If you like this project, please consider giving it a ⭐ on GitHub.
