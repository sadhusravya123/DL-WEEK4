AIM

Implementation of Regularization Techniques, including L1/L2 Regularization, Dropout, Early Stopping, and Hyperparameter Tuning.

Objective

To understand and implement different techniques for reducing overfitting and improving the generalization of a deep learning model.

Dataset

MNIST Handwritten Digit Dataset

60,000 training images
10,000 test images
Image size: 28 × 28
10 classes (0–9)
Techniques Implemented
L1 Regularization – Adds a penalty based on absolute weight values.
L2 Regularization – Adds a penalty based on squared weight values.
Dropout – Randomly deactivates neurons during training.
Early Stopping – Stops training when validation performance stops improving.
Hyperparameter Tuning – Tests different learning rates, batch sizes, and L2 values.
Model
Flatten → Dense(64) → Dense(32) → Dense(16) → Dense(4) → Dense(10)

ReLU activation is used in hidden layers and Softmax in the output layer.

Hyperparameters
Parameter	Value
Optimizer	RMSprop
Loss	Sparse Categorical Crossentropy
Dropout	0.3
L1/L2	0.001
Epochs	20
Validation Split	20%
Evaluation

The models are evaluated using:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix
Conclusion

The experiment demonstrates how L1/L2 regularization, Dropout, Early Stopping, and Hyperparameter Tuning help reduce overfitting and improve model performance.
