# Diabetes Prediction Using Machine Learning

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
This project, developed during my internship at System Tron, focuses on predicting diabetes using machine learning techniques. The goal is to create a model that can accurately predict whether a person has diabetes based on various health parameters.

## Project Overview
Diabetes is a chronic disease that affects millions of people worldwide. Early detection is crucial for managing and treating the condition effectively. This project leverages machine learning algorithms to analyze patient data and predict the likelihood of diabetes.

## Features
- Data Preprocessing: Cleaning and preparing the dataset for analysis.
- Model Training: Training multiple machine learning models.
- Model Evaluation: Evaluating the models using various metrics.
- Prediction: Providing predictions based on user input.
- Web Interface: A user-friendly web interface for input and displaying predictions.

## Installation
To run this project locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/diabetes-prediction.git
    cd diabetes-prediction
    ```

2. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

3. **Set up the virtual environment (optional but recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

## Usage
To use the diabetes prediction tool, follow these steps:

1. **Run the application:**
    ```sh
    python app.py
    ```

2. **Open the web interface:**
    - Navigate to `http://localhost:5000` in your web browser.

3. **Input patient data:**
    - Enter the required health parameters (e.g., glucose level, BMI, age).

4. **Get the prediction:**
    - Click on the 'Predict' button to get the diabetes prediction.

## Dataset
The dataset used for this project is the Pima Indians Diabetes Dataset, which contains several health-related parameters. The dataset is available in the `data` directory.

- **Attributes:**
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (0 or 1 indicating the absence or presence of diabetes)

## Model
Multiple machine learning models are trained and evaluated for this project, including:

- Logistic Regression
- Decision Trees
- Random Forests
- Support Vector Machines (SVM)
- Neural Networks

Details about the models and their performance can be found in the `models` directory.

## Results
The performance of the models is evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC score. Detailed evaluation results and comparison of models are documented in the `results` directory.

## Contributing
We welcome contributions to improve this project. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements
I would like to thank System Tron for the opportunity to work on this project and the open-source community for providing invaluable resources and tools.
