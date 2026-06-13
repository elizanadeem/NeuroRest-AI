
# NeuroRest AI 🧠💤

## Overview

NeuroRest AI is a deep learning-based healthcare analytics system developed as a university Artificial Intelligence project.

The system analyzes sleep and lifestyle data to:

* Predict sleep disorders (None, Insomnia, or Sleep Apnea)
* Estimate a person's stress level
* Provide real-time predictions through an interactive Gradio interface

The project uses a multi-task neural network built with PyTorch that performs both classification and regression using a shared feature-learning backbone.

---

## Features

* Deep Learning model using PyTorch
* Multi-task learning architecture
* Sleep disorder prediction
* Stress level estimation
* Data preprocessing and feature engineering
* Model evaluation and performance metrics
* Interactive Gradio web application

---

## Technologies Used

* Python
* PyTorch
* Pandas
* NumPy
* Scikit-Learn
* Gradio

---

## Dataset

The model was trained using the Sleep Health and Lifestyle Dataset.

Features include:

* Age
* Gender
* Occupation
* Sleep Duration
* Quality of Sleep
* Physical Activity Level
* BMI Category
* Blood Pressure
* Heart Rate
* Daily Steps

---

## Model Architecture

The project implements a Multi-Task Neural Network consisting of:

* Shared feature extraction backbone
* Classification head for sleep disorder prediction
* Regression head for stress level prediction

This approach allows the model to learn common health-related patterns while solving multiple prediction tasks simultaneously.

---

## Results

The trained model can:

* Classify sleep disorders into:

  * None
  * Insomnia
  * Sleep Apnea

* Predict stress levels based on lifestyle and health indicators

---

## User Interface

A Gradio-based interface allows users to enter health and lifestyle information and receive instant predictions from the trained model.

---

## Project Type

University Artificial Intelligence Team Project

---

## Author
* Developed as a **Team Project** for [AI/ FAST NUCES].

---

## 🛠️ Contributors
This was a collaborative **Team Project** developed by:
* [Eliza Nadeem ](https://github.com/elizanadeem)
* [Rahmeen Nabeel](https://github.com/rahmeennabeel)
* [Zoha Sarwar](https://github.com/ZohaSarwar)
* [Aneeq Kamran](https://github.com/aneeqkamran90)

