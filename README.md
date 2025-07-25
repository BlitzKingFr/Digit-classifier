# MNIST Handwriting Digit Classifier

This project implements a handwritten digit recognition system based on the MNIST dataset using PyTorch.  
It takes images of handwritten digits (0-9), preprocesses them to match MNIST style, and predicts the digit using a trained deep learning model.

---

## Features

- Upload any handwritten digit image and get prediction.
- Preprocessing pipeline to convert any digit image to MNIST-compatible format:
  - Grayscale conversion
  - Inversion (white digit on black background)
  - Resizing with aspect ratio preservation
  - Centering the digit inside a 28x28 canvas
  - Normalization for model input
- Uses a PyTorch-trained convolutional neural network (CNN) model.
- Visualization of the processed digit alongside prediction.

---

## How to Use

1. Clone this repository.
2. Install dependencies:

   ```bash
   pip install torch torchvision matplotlib pillow

## Working
-  You can upload your own image(.png or .jpg) and upload it by running through the last cell.
-  There is also  testimages provided if you want to do it from there as well which is in the second to last cell just execute it.
