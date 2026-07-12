# BERT News Topic Classifier

## Overview

This project was developed as part of the **AI/ML Engineering Advanced Internship** at **DevelopersHub Corporation**.

The objective of this task is to fine tune the `bert-base-uncased` transformer model to classify news headlines into four topic categories using the AG News dataset. The project demonstrates the complete Natural Language Processing workflow, including data preprocessing, transformer fine tuning, model evaluation, and deployment through an interactive Gradio interface.

---

## Objectives

* Load and preprocess the AG News dataset.
* Fine tune the BERT transformer model for text classification.
* Evaluate the model using Accuracy and Macro F1 Score.
* Deploy the trained model with Gradio for real time predictions.

---

## Dataset

**Dataset:** AG News

The dataset contains news headlines categorized into four classes.

* World
* Sports
* Business
* Science and Technology

The dataset is provided by the Hugging Face Datasets library.

---

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Hugging Face Datasets
* Hugging Face Evaluate
* NumPy
* Gradio

---

## Project Workflow

### Data Loading

The AG News dataset is loaded directly from the Hugging Face Hub.

### Data Preprocessing

News headlines are tokenized using the BERT tokenizer with padding and truncation before being formatted for model training.

### Model Initialization

The pre trained `bert-base-uncased` model is configured with a four class sequence classification head.

### Model Training

The model is fine tuned using the Hugging Face Trainer API with optimized training arguments.

### Model Evaluation

The trained model is evaluated using Accuracy and Macro F1 Score on the validation dataset.

### Deployment

An interactive Gradio application allows users to classify custom news headlines in real time.

---

## Model Performance

| Metric | Score |
|---------|------:|
| Training Loss | 0.2892 |
| Validation Loss | 0.2900 |
| Accuracy | 89.93% |
| Macro F1 Score | 89.92% |

---

## Sample Predictions

Example headlines include:

* NVIDIA announces next generation AI processor architecture.
* Real Madrid wins the Champions League final.
* Central bank signals interest rate hikes.
* Diplomatic talks resume amid regional conflict.
* New software updates address security vulnerabilities.

---

## Repository Structure

```
.
├── BERT_News_Classifier.ipynb
├── README.md
├── License
└── .gitignore
```

---

## Internship Information

**Organization:** DevelopersHub Corporation

**Internship:** AI/ML Engineering Advanced Internship

**Task:** Task 1 — News Topic Classifier Using BERT

---

## Learning Outcomes

This project provided practical experience with transformer based Natural Language Processing, transfer learning, text preprocessing, model fine tuning, evaluation using classification metrics, and lightweight machine learning deployment using Gradio.
