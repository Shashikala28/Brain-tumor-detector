# 🧠 Brain Tumor Detection using Deep Learning

This project is a web-based application that detects brain tumors from MRI images using a deep learning model based on VGG16. Users can upload an image, and the system predicts whether a tumor is present and its type.

---

## 🚀 Features

- Upload MRI brain scan images
- Detect tumor presence
- Classify tumor types:
  - Pituitary
  - Glioma
  - Meningioma
  - No Tumor
- Display prediction with confidence score
- Simple web interface using Flask

---

## ⚙️ Installation

### 1. Clone the repository
git clone https://github.com/your-username/BrainTumorDetection.git
cd BrainTumorDetection

### 2. Create virtual environment
python -m venv .venv

### 3. Activate virtual environment
**Windows:**
.venv\Scripts\activate

### 4. Install dependencies
pip install flask tensorflow pillow numpy matplotlib seaborn scikit-learn

---

## ▶️ Run the Application

python main.py
Then open in browser:
http://127.0.0.1:5000/

---

## Model File

The trained model (.h5) is not included due to size limitations.

To run this project:
1. Download or train the model separately
2. Place it inside:
   backend/model/brain_tumor_model.h5

## 📸 How to Use

1. Open the web app in your browser  
2. Upload a brain MRI image  
3. Click submit  
4. View prediction and confidence score  

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Flask
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

