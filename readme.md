# Pneumonia Detection using Deep Learning

Welcome to the **Pneumonia Detection** project! This repository showcases a deep learning-based web application that detects pneumonia from X-ray images. With an intuitive interface built using Flask, HTML, JS, and CSS, this project aims to simplify pneumonia detection with just a few clicks. Let's dive in and see how you can recreate this awesome project! 🚀

## 🎯 Project Overview

This project uses a Convolutional Neural Network (CNN) trained on chest X-ray images to detect pneumonia. It leverages the powerful **VGG19** architecture for transfer learning, and the whole application is wrapped up in a neat and user-friendly web interface.

### Features:
- **Deep Learning Model**: Built using VGG19, fine-tuned for pneumonia detection.
- **Interactive UI**: Built with **Flask**, along with **HTML**, **CSS**, and **JavaScript** for an engaging user experience.
- **Ready-to-Use Deployment**: Easily recreate and deploy this project with all the provided guidelines.

## 📸 Dataset
The dataset used for this project consists of labeled chest X-ray images categorized into pneumonia and normal cases.

- You can find the dataset here: [Dataset Link](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## ⚙️ How to Recreate This Project
Follow these steps to get started with the pneumonia detection project.

### 1. Clone the Repository
First, clone the repository to your local machine:

```bash
$ git clone https://github.com/HAR5HA-7663/Pneumonia-Detection-Model.git
$ cd pneumonia-detection
```

### 2. Set Up Environment
Ensure you have **Python 3.x** installed. You can set up a virtual environment:

```bash
$ python -m venv venv
$ source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install the required dependencies:

```bash
$ pip install -r requirements.txt
```

### 3. Download the Dataset
Download the dataset from [Dataset Link](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) and place it in the appropriate directory (e.g., `chest_xray/`).

### 4. Train the Model
You can train the model by running the provided Jupyter Notebook in Google Colab. Access the Colab link here: [Colab Notebook](https://colab.research.google.com/drive/1dG1QVjrV6VBmMFMqQMU8d1ykK6vzO8j8?usp=sharing).

If you want to train it locally, use the Jupyter Notebook provided in the repository (`Pneumonia_Detection_Training.ipynb`).

### 5. Start the Web Application
After training the model, start the Flask server to interact with the app:

```bash
$ python app.py
```

Navigate to `http://127.0.0.1:5000/` in your web browser to interact with the application.

## 🖼️ Screenshots

### Main Interface:
![Main Interface](Screenshots\Screenshot 2024-12-02 230328.png) _(Replace this placeholder with an actual image link)_

<!-- ### Results:
![Detection Result](https://your-image-link.com) _(Replace this placeholder with an actual image link)_ -->

## 🛠️ Technologies Used
- **Python**: Programming language for building the backend.
- **Flask**: Web framework for creating the server.
- **TensorFlow/Keras**: For deep learning model implementation.
- **HTML, CSS, JavaScript**: For building the UI.
- **Google Colab**: For training the model in the cloud.

## 🤖 Model Architecture
The model leverages **VGG19** for feature extraction and transfer learning, followed by incremental unfreezing and full fine-tuning to achieve optimized performance on pneumonia detection.

## 🚀 Deployment
Deploying this web app is straightforward. You can either deploy it on a cloud platform like **Heroku**, **AWS**, or run it on your local server (Just Like us).

## 🙌 Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please feel free to fork the repository and create a pull request.

<!-- ## 📧 Contact
Feel free to reach out if you have any questions or ideas:
- **Email**: [harsha7663@gmail.com] _(Replace this placeholder)_
- **GitHub**: [Harsha Vardhan Yellela](https://github.com/HAR5HA-7663) -->

## 🌟 Acknowledgments
This project wouldn't be possible without the amazing open-source resources, tutorials, and support from the community.

### Made with ❤️ by CRE Team 7 
