# Instrument Classification Using CNNs

This project uses a Convolutional Neural Network (CNN) to classify audio files of various musical instruments. Audio files are converted into Mel spectrograms, which are then used as input for the CNN.

**Note**: The audio files used in this project are not included in the repository due to size constraints. However, they can be provided upon request. Please reach out if you need access to the dataset.

## Features
- Instruments to classify: Piano, Clarinet, Acoustic Guitar, Electric Guitar, Saxophone, Keyboard, Violin, Trumpet and Voice.
- Utilizes Mel spectrograms for feature extraction.
- Built with TensorFlow and Keras.

## Requirements
- Python 3.7 or higher
- TensorFlow
- NumPy
- Librosa
- OpenCV
- Scikit-learn
- Matplotlib

## Model
- Input: 128x128 grayscale Mel spectrograms
- 3 Convolutional layers with ReLU activation
- MaxPooling layers after each convolution
- Dense layers for classification
- Output: Softmax activation for multi-class classification
