# 🍱 FoodVision Big — PyTorch Implementation

> **EfficientNetB2-based feature extractor trained on 20% of the Food-101 dataset to classify 101 different food categories using PyTorch.**

An advanced image classification project built with **PyTorch**, designed to recognize **101 classes** of food from the Food-101 dataset using an **EfficientNetB2** architecture.  
Only **20% of the original Food-101 dataset** was used, showing how efficient architectures can handle large-scale classification even with limited data.  
[Download the model]([https://huggingface.co/spaces/Barkins/Food_Vision_Mini/blob/main/09_pretrained_effnetb2_feature_extractor_pizza_steak_sushi_20_percent.pth](https://huggingface.co/spaces/Barkins/Food_Vision_Big/resolve/main/09_pretrained_effnetb2_feature_extractor_food101_20_percent.pth?download=true))

---

## 🧠 Overview

This project extends the FoodVision Mini concept to a larger-scale classification problem — moving from **3 classes to 101 distinct food categories**.  
EfficientNetB2 allows for strong performance while keeping training efficient and manageable.

### Key Features
- Implemented entirely with **PyTorch**
- 101-class classification using **Food-101 dataset**
- Uses **EfficientNetB2** as the feature extractor
- Trained on only **20%** of the dataset for efficiency
- Includes scripts for **training, validation, and inference**
- Easily extendable for **fine-tuning or deployment**

---

## 🧩 Requirements

Install dependencies before running the project:

```bash
pip install torch torchvision torchaudio
pip install matplotlib
pip install numpy
pip install tqdm
pip install torchinfo
pip install pillow
```
## Feedback
For feedback or questions, contact: [barkin.adiguzel@gmail.com](mailto:barkin.adiguzel@gmail.com)

```
## Feedback
For feedback or questions, contact: [barkin.adiguzel@gmail.com](mailto:barkin.adiguzel@gmail.com)
