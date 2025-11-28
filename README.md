# 🧠 Early Stage Autism Spectrum Disorder (ASD) Detection using Deep Learning

This project focuses on detecting **early-stage Autism Spectrum Disorder (ASD)** using facial image classification through Deep Learning.  
A trained Convolutional Neural Network (CNN) model predicts whether an uploaded face image belongs to an **Autistic** or **Non-Autistic** individual.

This system supports early screening and research, helping enhance awareness and automated diagnosis assistance.

---

## 📌 Objectives

- To classify facial images into Autistic & Non-Autistic categories.
- Enable early ASD prediction through deep learning technology.
- Build an accurate, scalable model suitable for deployment.

---

## 🏗 Project Structure

Early-Stage-ASD/
│── dataset/ # ASD & Non-ASD images
│── model/ # Trained model (.h5/.pth)
│── code/ # Notebook / script files
│── app.py # Prediction script
│── requirements.txt # Dependencies
│── README.md # Documentation

---

## 🧠 Deep Learning Model Details

| Parameter | Value |
|----------|--------|
| Architecture | CNN |
| Input Size | 224×224 px |
| Loss Function | Binary Cross Entropy |
| Optimizer | Adam |
| Activation | Sigmoid |
| Output | Autistic / Non-Autistic |

Transfer Learning models such as **MobileNetV2, VGG16, EfficientNetB0** can also be integrated for better accuracy.

---

## 🔧 Tech Stack & Libraries

- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- OpenCV  
- Matplotlib  
- Scikit-Learn  
- Flask / Streamlit *(optional for UI)*

---

## ⚙ How to Run the Project

### Install dependencies
```bash
pip install -r requirements.txt

### Run prediction script
python app.py
Upload an image → Model returns the result with probability.

Input: child_face.jpg
Prediction → Autistic (0.89 probability)

📜 Disclaimer

This project is for research & educational use only
and is not an alternative to clinical diagnosis.

🤝 Contributions

Pull requests and suggestions are welcome!
If you'd like to collaborate or need help integrating UI/model — feel free to ask.


---

If you'd like, I can generate additional files for GitHub:

### 🔥 Available on request:
✔ `requirements.txt`  
✔ Proper project folder for GitHub  
✔ UI interface (Flask/Streamlit)  
✔ Model training code file  
✔ Documentation PDF

Just reply — **"Generate complete project files"** 🚀
