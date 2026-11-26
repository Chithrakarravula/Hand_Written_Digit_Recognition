# Handwritten Digit Recognition (CNN)

A convolutional neural network that recognizes handwritten digits (0-9), trained on the MNIST dataset with TensorFlow/Keras.

## Results
- Test accuracy: **98.34%** on 10,000 test images
- Test loss: 0.060

## Model
- 3 x (Conv2D 64 filters, 3x3, ReLU + MaxPooling 2x2)
- Flatten, then Dense 64, Dense 32, Dense 10 (softmax)
- Optimizer: Adam | Loss: sparse categorical crossentropy
- 5 epochs, 30% validation split

## Tech stack
Python, TensorFlow/Keras, NumPy, OpenCV, Matplotlib

## How to run
    pip install -r requirements.txt
    jupyter notebook handwritten_digit_recognition.ipynb

## Predict your own digit
Put a handwritten digit image in `samples/`, update the image path in the last cells of the notebook, and run them. The image is converted to grayscale, resized to 28x28 and passed to the model.

## Author
Chithra Karravula - [LinkedIn](your-linkedin-link)
