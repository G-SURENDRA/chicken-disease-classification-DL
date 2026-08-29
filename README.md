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


```
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

```





## ⚙️ Installation
### 1. Clone the repository
     git clone https://github.com/G-SURENDRA/chicken-disease-classification-DL.git

     cd chicken-disease-classification-DL
### 2. Create a virtual environment
    python -m venv venv
### 3. Activate the environment
   Windows
   venv\Scripts\activate
   Linux / macOS
   source venv/bin/activate
### 4. Install dependencies
    pip install -r requirements.txt




## ▶️ Running the Application

### Run the application using:

     python app.py

  Then open the local URL displayed by the application in your browser.

## 🔄 DVC Pipeline

DVC is used to manage the machine learning workflow and improve
reproducibility.

The project includes:

dvc.yaml

dvc.lock

.dvc/

.dvcignore


The pipeline can be reproduced using:

dvc repro


### 🧪 Model Evaluation

Model evaluation results are stored in:

scores.json

Current recorded performance:

Accuracy: 95.80%
Loss:     0.1153


## 📷 Application

The project includes a local web application that allows users
to provide an image and obtain a disease classification prediction.



## 🚀 Future Improvements
Improve model generalization with additional training data

Add more disease categories

Perform systematic hyperparameter optimization

Add confusion matrix and detailed classification metrics

Add automated model testing

Deploy the application to a cloud platform

Add model monitoring

Improve the prediction interface


## 👨‍💻 Author

G-SURENDRA

### GitHub:
     https://github.com/G-SURENDRA

## 📄 License

This project is licensed under the MIT License.


### ⚠️ One important correction

I deliberately **didn't claim specific disease classes**, because I don't want to invent information that isn't visible in the repository's current top-level documentation.

Also, I wrote **95.80%**, not "96%" — because your actual `scores.json` gives `0.958031833...`. :contentReference[oaicite:4]{index=4}





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
