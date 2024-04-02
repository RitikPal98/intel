# Tumor Detection Chatbot

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Intel_logo_%282020%2C_light_blue%29.svg/300px-Intel_logo_%282020%2C_light_blue%29.svg.png" width="50">](https://www.intel.com/)
[<img src="https://www.intel.com/content/dam/develop/public/us/en/images/admin/oneapi-logo-rev-4x3-rwd.png" width="50">](https://www.intel.com/)
[![React](https://img.shields.io/badge/React-%2300D8FF.svg?style=flat&logo=react&logoColor=white)](https://reactjs.org/)
[![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=flat&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-%23F37626.svg?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-%2334D058.svg?style=flat&logo=hugging-face&logoColor=white)](https://huggingface.co/)

This project implements a chatbot interface for tumor detection using deep learning. The backend is built with Flask, and the frontend is developed with React. The chatbot accepts image uploads and provides responses indicating whether a tumor exists in the uploaded image.

## Features

- **Image Upload:** Users can upload images of medical scans for tumor detection.
- **Real-time Response:** Chatbot provides real-time responses indicating the presence of a tumor.
- **Simple Interface:** User-friendly interface resembling a chat application.

## Requirements

- Python 3.6+
- Node.js
- npm or yarn

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/username/tumor-detection-chatbot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd tumor-detection-chatbot
   ```

3. Install backend dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Install frontend dependencies:

   ```bash
   npm install
   ```

## Usage

1. Start the backend server:

   ```bash
   python app.py
   ```

2. Open your browser and navigate to `http://127.0.0.1:5000/` to access the chatbot interface.

# Leveraging Intel Developer Cloud for Tumor Detection Model Training 🌐💻

Utilizing the resources provided by Intel Developer Cloud has significantly expedited our tumor detection model's development and deployment processes. Intel's advanced CPU and XPU capabilities, combined with optimized deep learning frameworks, have revolutionized our approach to medical image analysis. 💻⚡

## Tumor Detection Model Training

The Intel Developer Cloud's powerful computing infrastructure, coupled with the utilization of optimized deep learning frameworks such as TensorFlow tailored for Intel architectures, has drastically enhanced the efficiency of our model training pipeline. By harnessing the computational prowess of Intel's hardware resources and optimized software stack, we have achieved remarkable improvements in training efficiency and performance. 🚀🔧

The integration of oneDNN, Intel's high-performance deep learning library, has further accelerated our training process by optimizing the computational tasks involved in tumor detection model training. With the assistance of oneDNN, we have witnessed significant reductions in training time, allowing for faster model optimization and experimentation cycles. 🚀⚒️

In practical terms, the training time for a single epoch has been drastically reduced compared to alternative platforms, with Intel Developer Cloud enabling us to achieve epoch times as low as 3 seconds, representing a substantial improvement in efficiency. This expedited training process has empowered us to iterate more rapidly, fine-tune our model architecture, and enhance the accuracy of tumor detection on MRI scans. 🏋️‍♂️🧑‍💻

## Conclusion

Overall, the collaborative utilization of Intel Developer Cloud's advanced computing infrastructure, optimized deep learning frameworks, and high-performance libraries has been pivotal in accelerating the development and deployment of our tumor detection model. This advancement contributes to improved patient care and outcomes in the field of medical imaging. 🩺🔬

## Demonstration of the Project

[![Click here to watch the demo video](https://img.youtube.com/vi/oBRMdQpaP50&t=16s/0.jpg)](demo-final.mp4)

## Tumor Prediction and Result Generation 🛍️💡

This code snippet showcases the implementation of a tumor detection model using deep learning techniques. Leveraging state-of-the-art convolutional neural networks (CNNs) such as ResNet or VGG, the model analyzes MRI scan images to identify the presence of tumors.

The tumor detection process involves preprocessing MRI scan images, feeding them into the CNN-based model for feature extraction, and then applying classification algorithms to predict the presence or absence of tumors. Additionally, transfer learning techniques can be utilized to fine-tune pre-trained CNN models on medical imaging datasets, thereby enhancing the model's performance on tumor detection tasks.

By leveraging deep learning and medical imaging expertise, this model offers accurate and reliable tumor detection capabilities, aiding healthcare professionals in diagnosing and treating patients effectively. 🧠💻🏥🔬

<div style="display: flex; flex-wrap: wrap;">
   <img src="https://lh3.googleusercontent.com/drive-viewer/AKGpihbnXHL_5l-1dXs_h5BvbtfuBv9JWInxRAGFoAeJv8BPHi7UGmlnBAzequmfWfIGAPBlP-4LxvzIu55lMQqLLcaGGhyiHQ=w3200-h1730" width="400" alt="Image 4">
    <img src="https://lh3.googleusercontent.com/drive-viewer/AKGpihYYm9zgS2zolQ1tz5GJSQUIswmzohUwuPYZx4-vB25R3MFG2tXbjcMPtolp22ioYGC2J_FHHAcMjHxRDvy28jMY7XD1Xg=w3200-h1730-v0" width="400" alt="Image 1">
    <img src="https://lh3.googleusercontent.com/drive-viewer/AKGpihZAeWkEMeWZbErWUc5kTAup4I0XRYs2fA8poB1VRcfW-cYtGNz4miyPb0yC6TY2qQwXxWWBoeEsQ-vvmeOH9IxqlcrO8w=w3200-h1730-v0" width="800" alt="Image 2">
    <img src="https://lh3.googleusercontent.com/drive-viewer/AKGpihZX0NRt2aK3ZY-mwZt0bZWs48DuuPuSYiAAFmoXCVWjD-DQT4n4lE2glr8yjAjmjaDPoM7IyVl_S8S2Z5dGMwgX6AKPHQ=w3200-h1730-v0" width="800" alt="Image 3">
   
</div>

# Built With 🛠️

1. **Backend - Flask:** Our application's backend and server functionality are powered by Flask, a lightweight and flexible web framework for Python. Flask enables us to handle server-side logic efficiently, process uploaded MRI scan images, and invoke machine learning models for tumor detection. 🐍🚀

2. **Machine Learning Models - TensorFlow and OpenCV:** The core functionality of tumor detection is implemented using TensorFlow, a powerful framework for building and training neural networks. Additionally, OpenCV, a computer vision library, is utilized for image preprocessing, feature extraction, and post-processing tasks, enhancing the accuracy and reliability of tumor detection from MRI scan images. 🧠⚙️🔬

3. **Intel Developer Cloud:** Leveraging Intel's high-performance CPU and XPU capabilities, we accelerate model inference processes, reducing processing time and improving the efficiency of tumor detection from MRI scan images. ⚡💻

This tech stack enables us to deliver a robust and efficient tumor detection application, providing users with accurate and timely insights into their medical condition. 🩺🔬🔍

# What It Does 🤖🚀

Our application revolutionizes the field of medical imaging by providing an efficient and accurate solution for tumor detection from MRI scan images. Here's a breakdown of its key functionalities:

1. **Image Upload for Tumor Detection: 📷🔍**

   - Users can upload MRI scan images of patients through the frontend interface for tumor detection.
   - The application accepts MRI scan images in standard formats and provides users with a simple and intuitive interface to upload their medical images.

2. **Model Processing Using TensorFlow and OpenCV: 🧠⚙️🔬**

   - Upon image upload, the application processes the MRI scan images using TensorFlow and OpenCV libraries to detect the presence of tumors.
   - TensorFlow is utilized to build and train deep learning models for tumor detection, leveraging convolutional neural networks (CNNs) for feature extraction and classification tasks.
   - OpenCV is employed for image preprocessing, augmentation, and post-processing tasks to enhance the accuracy and reliability of tumor detection.

3. **Output Prediction of Tumor Presence: 🔮💡**

   - After processing the MRI scan images, the application generates predictions indicating the presence or absence of tumors.
   - Users receive clear and actionable insights into the status of their medical condition, aiding healthcare professionals in diagnosis and treatment planning.

In summary, our application leverages the power of TensorFlow and OpenCV to offer efficient and reliable tumor detection capabilities from MRI scan images. With a user-friendly interface, we aim to improve healthcare outcomes and enhance patient care in the field of medical imaging. 🌐🔬💊
