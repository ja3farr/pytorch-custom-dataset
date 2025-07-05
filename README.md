# 🧠 PyTorch Custom Dataset Learning Project

This project is part of my PyTorch learning journey. It demonstrates how to load and preprocess custom image datasets, then train a basic CNN model using PyTorch’s Dataset and DataLoader utilities.

---

## 📌 Highlights

- Walk through directories of images and automatically generate a labeled dataset (`labels.csv`)
- Implement a custom PyTorch `Dataset` class
- Apply common image transformations (resize, rotate, etc.)
- Prepare datasets using `DataLoader`
- **Define and train a simple CNN model on the custom dataset**
- Track training loss across epochs

--- 

## 🔗 Dataset Source
[Dataset on Kaggle](https://www.kaggle.com/datasets/eneskosar19/happy-or-sad-binary-image-classification)

---

## 🧠 Training Info

Model: Simple CNN with Conv2D, ReLU, MaxPool, Linear

Loss: CrossEntropyLoss

Optimizer: Adam

This is an educational project — it's not optimized for accuracy or deployment.

---

## 📁 Project Files

- `generate_labels.ipynb` — Create labeled CSV from image folders  
- `custom_dataset.ipynb` — Load dataset, apply transforms, and train CNN  
- `requirements.txt` — Dependencies used in the project  

---

## 👤 Author
[Ja3far Yousef](https://github.com/ja3farr)