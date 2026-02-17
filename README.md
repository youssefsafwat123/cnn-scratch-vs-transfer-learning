# Intel Image Classification: Scratch CNN vs. Transfer Learning

This project explores two different approaches to classifying landscape images (Buildings, Forest, Glacier, Mountain, Sea, Street) using the Intel Image Dataset.

## 🚀 Project Overview
The goal was to compare a custom-built Convolutional Neural Network (CNN) against a pre-trained professional model using Transfer Learning.

## 🏗️ Methodologies
1. **Custom CNN (From Scratch):** - 3 Convolutional blocks with MaxPooling.
   - Dense layers with Dropout for regularization.
2. **Transfer Learning:**
   - Base Model: **MobileNetV2** (Pre-trained on ImageNet).
   - Global Average Pooling with a custom classification head.

## 📊 Results
- **Scratch Model:** Reached ~85% training accuracy (showed signs of overfitting).
- **Transfer Learning:** Achieved high validation stability (~78%+) with much faster training times per epoch.
