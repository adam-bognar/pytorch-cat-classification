# 🐱 Cat Breed Classifier (PyTorch + Transfer Learning)

This project classifies cat images into one of three breeds: **Maine Coon**, **Manx**, or **Ragdoll** using a fine-tuned ResNet18 model.

## 🚀 Features

- ✅ Custom CNN and Transfer Learning comparison
- ✅ Transfer learning with ResNet18 (pretrained on ImageNet)
- ✅ Fine-tuning for better performance
- ✅ Achieves ~79.5% test accuracy
- ✅ Confusion matrix evaluation
- ✅ Handles custom test images

---

## 📁 Dataset

The dataset is downloaded from [KaggleHub](https://github.com/kaggle/kagglehub) and contains images of 66 cat breeds. For this project, only 3 breeds are selected.

Directory structure:
data/
└── cat-breeds/
├── maine_coon/
├── manx/
└── ragdoll/


---

## 🏗️ Model

### CNN (Baseline)
- 3 convolutional blocks
- BatchNorm + Dropout
- ~60% accuracy

### ResNet18 (Transfer Learning)
- Freeze backbone initially
- Fine-tune entire network
- Achieves up to **~80% test accuracy**

---

## 📊 Evaluation

- Training + Validation accuracy/loss tracked across epochs
- Confusion matrix visualizes class-wise performance
