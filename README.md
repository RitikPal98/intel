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

## Configuration

- Backend configuration settings can be found in `config.py`.
- Frontend configuration settings can be found in `src/config.js`.
