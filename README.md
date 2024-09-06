# A-Deep-OCR-Model: A Deep Learning Model for Reading Sequential Numbers on Pictures

- The objective is to build and train a deep learning model using TensorFlow to recognize five-digit numbers from images. The task involves creating a synthetic dataset with 180,000 samples, which is splitted into training, validation, and test sets, each accompanied by their corresponding labels.
- The model constructed combines a Convolutional Recurrent Neural Network (CRNN) with Long Short-Term Memory (LSTM) layers to effectively capture both spatial and sequential patterns in the data.
- The model constructed misidentifies only 3 pictures that contain extremelly blurred or partly cropped numbers over 60,000 samples in each of the training, validation, and test sets. 
