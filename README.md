🧠 Skin Cancer Classification using CNN

This project is a Deep Learning model built using Convolutional Neural Networks (CNN) to classify skin lesion images into:
- Benign (0)
- Malignant (1)

The goal is to help in early detection of skin cancer using image classification.

---

📊 Dataset

The dataset contains dermoscopy images of skin lesions divided into:
- Training set
- Validation set
- Test set

Classes:
- Benign
- Malignant

---

 🏗️ Model Architecture

The model is built using TensorFlow and Keras:

- Rescaling (Normalization)
- Conv2D + ReLU activation layers
- MaxPooling layers
- Flatten layer
- Dense layers
- Output layer with Sigmoid activation

---
 ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Scikit-learn
- Matplotlib

---
 🔥 Data Preprocessing

- Image resizing (224x224)
- Normalization (1/255)
- Data Augmentation (Flip, Rotation, Zoom)
- Train/Validation split

---

 📈 Evaluation Metrics

The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🧪 Results

The model achieved good performance on test data with balanced evaluation metrics, especially focusing on Recall due to the medical importance of minimizing false negatives.

---

## 🚀 How to Run

1. Load dataset in Kaggle or local environment
2. Run preprocessing pipeline
3. Train the CNN model
4. Evaluate on test data

```python
model.fit(train_data, validation_data=val_data, epochs=10)
model.evaluate(test_data)
