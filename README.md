
# 🧠 Skin Cancer Detection with CNN

A deep learning web application that classifies skin lesions as **Benign** or **Malignant** using Convolutional Neural Networks (CNNs). Built with TensorFlow/Keras and deployed using Streamlit.

---





## 🧰 Tech Stack

- **Frontend:** Streamlit  
- **Backend & ML:** Python, TensorFlow, Keras  
- **Model Architecture:** CNN  
- **Visualization:** Matplotlib  
- **Deployment Ready On:** Render, Hugging Face Spaces, or Streamlit Cloud

---

## 📁 Project Structure

```
skin-cancer-detection-cnn/
├── main.py                # Streamlit app
├── skin_cancer_model.h5   # Trained model (not included in repo)
├── README.md
├── requirements.txt
└── ...
```

---

## 🔗 Download the Model

Due to GitHub's file size limits, the trained model is not included in this repository.

👉 **[Download skin_cancer_model.h5 from Google Drive](https://drive.google.com/file/d/1PIukYeFLCgZEXRVrs7XXmyu-8x7QCnQd/view?usp=drive_link)**  
Place the file in the root directory of this project.

---

## 🧠 How It Works

1. Upload a dermatoscopic image through the Streamlit app.
2. The image is resized, normalized, and passed to a CNN.
3. The CNN predicts one of two classes:
   - **Benign** (non-cancerous)
   - **Malignant** (cancerous)
4. The result is displayed immediately in the UI.

---

## 🏗️ Run Locally

```bash
git clone https://github.com/yourusername/skin-cancer-detection-cnn.git
cd skin-cancer-detection-cnn
pip install -r requirements.txt
streamlit run main.py
```

**Ensure** you’ve downloaded `skin_cancer_model.h5` and placed it in the same directory as `main.py`.

---

## ✅ Features

- Clean and simple web interface using Streamlit  
- Real-time prediction from uploaded skin lesion images  
- Binary classification: **Benign** or **Malignant**  
- Ready for deployment on public platforms

---

## 📊 Model Overview

- Input: RGB images, 224×224  
- Layers: Convolutional + MaxPooling + Dropout + Dense  
- Activation: ReLU and Sigmoid  
- Output: Binary (0 or 1)  
- Training Data: Dermatoscopic lesion dataset (e.g., ISIC)


## 🤝 Contributing

Feel free to fork this project, open issues, or suggest improvements!

---

## 🙋‍♂️ Author

**Prakamya Tripathi**  
[GitHub](https://github.com/prakamyaa) • [LinkedIn](https://www.linkedin.com/in/prakamya)

---

