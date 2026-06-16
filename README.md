This project implements a Convolutional Neural Network (CNN) for image classification on the CIFAR-10 dataset using TensorFlow and Keras.

The project begins with a baseline CNN model and then improves performance using Batch Normalization and Dropout regularization techniques.

DATASET
CIFAR-10 contains 60,000 color images belonging to 10 classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

Dataset Split:

- Training Images: 50,000
- Test Images: 10,000

Image Size:

- 32 × 32 pixels
- RGB Color Images

---

Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-Learn

---

## Model Architecture

### Baseline CNN

Conv2D → MaxPooling → Conv2D → MaxPooling → Flatten → Dense → Output

### Improved CNN

Conv2D → BatchNormalization → Conv2D → MaxPooling → Dropout

Conv2D → BatchNormalization → Conv2D → MaxPooling → Dropout

Flatten → Dense(128) → BatchNormalization → Dropout → Output

---

## Results

| Model | Accuracy |
|---------|----------|
| Baseline CNN | 70.29% |
| Improved CNN | 79.56% |

Accuracy Improvement:

+9.27%

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Training and Validation Curves

---

## Key Learnings

- Convolutional Neural Networks (CNNs)
- Feature Extraction
- Max Pooling
- Batch Normalization
- Dropout Regularization
- Overfitting Prevention
- Deep Learning Model Evaluation

---

## Future Improvements

- Data Augmentation
- Transfer Learning (ResNet, MobileNet)
- Hyperparameter Tuning
- Advanced CNN Architectures

---

## Author
Hussain Abbas
