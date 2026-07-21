# Bias-Resistant Visual Question Answering with Image-Question Fusion

## Project Overview

This project investigates whether Visual Question Answering (VQA) models truly use image information or mainly rely on question text.

Three models were compared:

- Text-only Model
- Image-only Model (Pretrained ResNet18)
- Fusion Model (Question + Image)

The project uses a Yes/No subset of the VQA v2 dataset.

---

## Dataset

Dataset: VQA v2

Subset Used:
- 777 Question-Image Pairs
- 545 Images
- Binary Answers (Yes / No)

---

## Models

### Text-only
- TF-IDF
- Logistic Regression

### Image-only
- Frozen ResNet18
- Logistic Regression

### Fusion
- TF-IDF + ResNet18 Features
- Logistic Regression

---

## Results

| Model | Accuracy |
|--------|----------|
| Text Only | 52.56% |
| Image Only | 50.64% |
| Fusion | 50.00% |

---

## Folder Structure

```
Project11_Bias_Resistant_VQA/

data/
models/
outputs/
reports/
presentation/

Project11_Bias_Resistant_VQA.ipynb
README.md
requirements.txt
```

---

## Author

Mihir Rami

M.Sc. Software Engineering