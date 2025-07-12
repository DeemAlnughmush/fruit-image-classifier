#  Fruit Image Classifier with Teachable Machine

This project demonstrates how to train an image classification model using [Teachable Machine by Google](https://teachablemachine.withgoogle.com/).  
The model distinguishes between **grape**, **strawberry**, and **blueberry** images.

---

##  Model Info

- Trained on: **Teachable Machine**
- Exported as: **TensorFlow → Keras**
- Classes:
  - 🍇 Grape
  - 🍓 Strawberry
  - 🫐 Blueberry

---

##  How It Works

A Python script running in **Google Colab**:
- Loads the trained model (`keras_model.h5`)
- Loads the class names from `labels.txt`
- Accepts a test image from the user
- Preprocesses the image to match the model input
- Predicts the fruit type and shows the **confidence percentage**

---

##  Files in this Repository

| File | Description |
|------|-------------|
| `keras_model.h5` | Trained model |
| `labels.txt` | Class labels |
| `fruit_classifier.ipynb` | Google Colab notebook with full code |
| `result-fruit-classifier.png` | Sample output after prediction |

---

##  Sample Output
 Class: Grape 
 
 Confidence Score: 97.95%

 
---

##  Compatibility

To run this notebook successfully:
- Use **TensorFlow 2.12.1**
- Python version should be **3.8, 3.9, or 3.10**
- Works on **Google Colab**

Install TensorFlow with:

```bash
pip install tensorflow==2.12.1

