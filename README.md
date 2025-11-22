# Cat-vs-Dog-Classifier

This is a Convolutional Neural Network (CNN) model built using **TensorFlow/Keras** to classify images of cats and dogs. 

---


The model takes **256x256 RGB images** as input and outputs the probability of the image belonging to the "dog" class.  

---

## Techniques Used
- **Adam Optimizer**: Adaptive learning rate for faster convergence.
- **Batch Normalization**: Improves stability and speeds up training.
- **Dropout**: Prevents overfitting (0.25 dropout rate after dense layers).
- **L2 Regularization**: Reduces overfitting.
- **Data Preprocessing**: Images resized to 256x256 and normalized.

---

## Result
- This model achieves the 92% accuracy. With data augmnetation, Hyperparameter tuning and more epochs this can be improve more.
- Also we can do the transfer learning using pretrained models.

---
**Mehak Imran | AI Engineer**
