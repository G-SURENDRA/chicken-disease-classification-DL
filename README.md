# chicken-disease-classification-DL


# 🐔 Chicken Disease Classification using Deep Learning

A deep learning-based computer vision system for classifying
chicken diseases from images using a Convolutional Neural Network (CNN).

The project is developed as a modular machine learning pipeline with
data versioning using DVC, configurable training, model evaluation,
and a local web application for predictions.

---

## 🎯 Problem

Chicken diseases can significantly affect poultry health and production.
Manual identification from symptoms or images can be time-consuming
and may require expert knowledge.

This project aims to assist disease identification by automatically
classifying chicken images using a trained deep learning model.

---

## 💡 Solution

The system takes a chicken image as input and uses a CNN-based
deep learning model to predict the corresponding disease class.

The project follows a structured ML pipeline covering:

- Data ingestion
- Data preprocessing
- Model training
- Model evaluation
- Model prediction
- Local application deployment
- Data/model pipeline management using DVC

---

## ✨ Features

- 🧠 CNN-based image classification
- 🖼️ Image-based disease prediction
- ⚙️ Modular ML pipeline
- 📊 Model evaluation
- 🔄 DVC-based pipeline management
- 🧪 Testing support
- 🌐 Local web application
- ⚙️ Configuration-driven workflow
- 🔁 Reproducible ML workflow

---

## 🧠 Machine Learning Model

The project uses a **Convolutional Neural Network (CNN)** for
image classification.

### Model Performance

| Metric | Result |
|---|---:|
| Accuracy | **95.80%** |
| Loss | **0.1153** |

> Results are based on the metrics recorded in `scores.json`.

---

## 🏗️ Project Architecture

```text
                    Chicken Image
                         │
                         ▼
                ┌─────────────────┐
                │ Data Ingestion  │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Data Processing │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │   CNN Model     │
                │    Training     │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Model Evaluation│
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Disease         │
                │ Prediction      │
                └─────────────────┘

```


## 🛠️ Tech Stack
### Programming

Python

### Machine Learning / Deep Learning

TensorFlow

Keras

Convolutional Neural Networks

NumPy

### MLOps / Workflow

DVC

YAML configuration

GitHub Actions

### Application

Python web application

HTML

CSS

### Development Tools

Git

GitHub



## 📂 Project Structure


chicken-disease-classification-DL/
│
├── .dvc/
├── .github/
│   └── workflows/
│
├── config/
├── research/
│
├── src/
│   └── cnnClassifier/
│
├── static/
├── templates/
│
├── app.py
├── main.py
├── test.py
│
├── dvc.yaml
├── dvc.lock
├── params.yaml
├── scores.json
│
├── requirements.txt
├── setup.py
├── .gitignore
├── .dvcignore
├── LICENSE
└── README.md




## Workflows
1.Update config.yaml

2.Update secrets.yaml [Optional]

3.Update params.yaml

4.Update the entity

5.Update the configuration manager in src config

6.Update the components

7.Update the pipeline

8.Update the main.py

9.Update the dvc.yaml
