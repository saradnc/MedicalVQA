## MedicalVQA

Domain-Adaptive Pretraining of BLIP Model for Medical Visual Question Answering

This repository presents a methodology for adapting the BLIP (Bootstrapping Language-Image Pretraining) model to the medical domain, enhancing its performance on medical VQA tasks. The approach involves domain-adaptive pretraining followed by fine-tuning on medical datasets.

## 📘 Overview

MedicalVQA aims to bridge the gap between general-purpose vision-language models and the specialized requirements of medical image understanding. By leveraging domain-adaptive pretraining, this work tailors the BLIP model to comprehend and respond to medical queries with higher accuracy.

## 🧪 Methodology

Domain-Adaptive Pretraining: The BLIP model is pre-trained on a corpus of medical images and associated textual descriptions to adapt its understanding to the medical domain.

Fine-Tuning: Post pretraining, the model is fine-tuned on specific medical VQA datasets to optimize its performance on tasks requiring detailed medical knowledge.

## 📁 Repository Structure
- `25-best-sistemato.ipynb` — Jupyter notebook showcasing model evaluation  
- `Paper.pdf` — Research paper detailing the methodology  
- `Presentation.pdf` — Presentation Slides

## 🚀 Getting Started
Prerequisites

Python 3.8+

PyTorch

Hugging Face Transformers

BLIP Model Weights

Installation

Clone the repository:

git clone https://github.com/saradnc/MedicalVQA.git
cd MedicalVQA


Install necessary dependencies:

pip install -r requirements.txt

Usage

Domain-Adaptive Pretraining: Utilize the provided scripts to initiate the pretraining process on your medical image-text dataset.

Fine-Tuning: After pretraining, fine-tune the model on a medical VQA dataset using the fine-tuning scripts.

## 📊 Results

The domain-adaptive pretraining approach has shown improvements in the model's ability to understand and answer medical questions accurately,with an improvement of 8% accuracy as demonstrated in the accompanying Jupyter notebook.



## 📬 Contact

For questions or collaborations, please reach out to:
📧 Email: sara.zappia794@gmail.com

