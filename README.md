# COVID-19 Detection using Deep Learning with X-ray Images

This repository contains the code and documentation for the final year project titled "Detection de COVID-19 à l'aide de l'apprentissage profond avec les images X-ray" by Sabbahi Mohamed Amine.

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Objective](#objective)
- [Importance of AI](#importance-of-ai)
- [Project Structure](#project-structure)
- [Technologies and Tools Used](#Technologies-and-Tools-Used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

## Introduction
The emergence of COVID-19 in March 2019 brought about a global health crisis. This project aims to provide a solution to rapidly and accurately detect COVID-19 using deep learning algorithms applied to X-ray images.

## Problem Statement
PCR tests, though accurate, are expensive and time-consuming. This project addresses the need for a faster and cost-effective method to detect COVID-19, using deep learning and convolutional neural networks (CNNs).

## Objective
The main objective of this project is to develop a CNN-based model to detect COVID-19 from X-ray images and deploy this model in a web application using the Flask framework.

## Importance of AI
Artificial intelligence, particularly deep learning, has shown significant potential in medical imaging. This project leverages AI to enhance the accuracy and speed of COVID-19 detection, which is crucial in controlling the spread of the virus.

## Project Structure

```
├── Proposed models              # Directory containing proposed model versions and sample images
│   ├── Proposed model N01       # Proposed model version 01
│   ├── Proposed model N02       # Proposed model version 02
│   ├── Proposed model N03       # Proposed model version 03
│   ├── negative patient.png     # Sample X-ray image of a negative COVID-19 patient
│   ├── negative.jpeg            # Another sample X-ray image of a negative COVID-19 patient
│   ├── positive patient.png     # Sample X-ray image of a positive COVID-19 patient
│   ├── positive.jpg             # Another sample X-ray image of a positive COVID-19 patient
│   └── test code.png            # Sample code or image for testing purposes
├── Trained_model                # Directory containing the trained model
│   └── model.h5                 # The trained model file in HDF5 format
├── static                       # Directory for static files (CSS, JavaScript, images)
├── templates                    # Directory for HTML templates
│   └── index.html               # Main HTML template for the web application
├── README.md                    # Project documentation
├── app.py                       # Flask application script
└── requirements.txt             # List of required Python packages
```
## Technologies and Tools Used
   - Programming Languages: Python
   - Deep Learning Frameworks: TensorFlow, Keras
   - Web Framework: Flask
   - Data Processing and Analysis: NumPy, Pandas
   - Visualization: Matplotlib, Seaborn
   - Model Deployment: Flask
   - Version Control: Git
   - IDE: Jupyter Notebook, Visual Studio Code

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/amine-sabbahi/Covid19-test-Web-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Covid19-test-Web-app
    ```
3. Create a virtual environment:
    ```sh
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```
5. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. To start the web application, run:
    ```sh
    python app.py
    ```
2. Access the web application at `http://localhost:5000`.



## Results
The model achieved significant accuracy in detecting COVID-19 from X-ray images. Detailed results and performance metrics can be found in the `results` folder.

## Contributors
- **Sabbahi Mohamed Amine** - [Github](https://github.com/amine-sabbahi)

---

**Université Abdelmalek Essaadi** Faculté des Sciences de Tetouan
   - Département : Génie Informatique
   - Licence : Science Math Informatique
   - Sujet : Projet du fin d'etude
   - Encadré par : Pr . ABDOUN OTMANE