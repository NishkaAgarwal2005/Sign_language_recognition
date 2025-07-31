

#  Sign Language Recognition Web Application

A real-time web application that detects and interprets sign language gestures using computer vision and machine learning. Built to bridge the communication gap between the hearing and speech impaired and the rest of the world.

##  Features

- 📷 Real-time hand gesture detection via webcam
- 🧾 Translates sign language into text (and optionally speech)
- 🎯 Custom-trained machine learning / deep learning model
- 🌐 User-friendly web interface
- 🔁 Supports continuous predictions
- 🚀 Deployable on local or cloud platforms

##  Tech Stack

- **Frontend:** HTML, CSS, JavaScript (or React/Streamlit, depending on your stack)
- **Backend:** Python, Flask (or FastAPI / Node.js if different)
- **Model:** Convolutional Neural Network (CNN) / TensorFlow / PyTorch
- **Computer Vision:** OpenCV / Mediapipe
- **Deployment:** Streamlit Cloud / Heroku / Render / AWS / GitHub Pages (optional)
- **Others:** NumPy, Pandas, Scikit-learn



##  How It Works

1. **Data Collection:** Images of hand gestures for different signs were collected and preprocessed.
2. **Model Training:** A CNN was trained to classify each gesture.
3. **Prediction Pipeline:**
   - Webcam input captured using OpenCV
   - Frame processed and passed to the model
   - Predicted output displayed on screen

##  Getting Started

### Clone the Repository

```bash
git clone https://github.com/NishkaAgarwal2005/sign_language_recognition.git
cd sign_language_recognition
