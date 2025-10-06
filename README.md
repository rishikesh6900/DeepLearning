🧮 MNIST Digit Classification with Keras & TensorFlow

This project demonstrates handwritten digit classification using the MNIST dataset with neural networks built in TensorFlow/Keras. It starts from a simple single-layer model and gradually improves accuracy by adding hidden layers, using the Flatten layer, and applying better activation functions.

📌 Overview

Dataset: MNIST (70,000 images of digits 0–9, 28×28 grayscale).

Goal: Classify digits (0–9) from images.

Frameworks: TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn.

🔄 Workflow

Load and explore the MNIST dataset.

Preprocess data (normalize pixel values and flatten images).

Build different neural network models:

Single-layer network.

Network with one hidden layer (ReLU).

Network using the Flatten layer for better preprocessing.

Train models using Adam optimizer and sparse categorical crossentropy loss.

Evaluate accuracy on test data.

Generate predictions and visualize confusion matrix.

📊 Results

Single-layer model: ~92% accuracy.

With hidden layer (ReLU): ~97% accuracy.

Final model (Flatten + ReLU + Softmax): ~97–98% accuracy.

🚀 Future Improvements

Use Convolutional Neural Networks (CNNs) for higher accuracy (~99%).

Add dropout layers to reduce overfitting.

Experiment with optimizers (SGD, RMSprop).

Hyperparameter tuning for learning rate, batch size, and epochs.

📝 License

This project is licensed under the MIT License.
