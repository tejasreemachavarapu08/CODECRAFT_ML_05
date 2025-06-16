# 🍕 Food Image Recognition & Calorie Estimation

This project uses a **Convolutional Neural Network (CNN)** to recognize food items from images and estimate their **calorie content**, helping users track their diet visually.

---

## 🧠 Objective
Classify food from images and assign approximate calorie values to each class.

---

## 📁 Dataset
- Source: Kaggle Food-101 (simplified subset)
- Classes: E.g., Burger, Pizza, Salad, etc.
- Manual calorie mapping added for each class

---

## ⚙️ Model Details
- CNN using Keras (Conv2D → MaxPooling → Flatten → Dense)
- Optimizer: Adam
- Accuracy: _[your result]_

---

## 🔢 Calorie Estimation
Each food class is mapped to an approximate calorie value:
```python
{'Pizza': 285, 'Burger': 354, 'Salad': 152, ...}
