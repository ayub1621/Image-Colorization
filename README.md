# Image Colorization using Autoencoder and VGG16 Transfer Learning

This program performs image colorization using an autoencoder with transfer learning, specifically utilizing the VGG16 model as a feature extractor. The program is implemented in Jupyter Lab.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Introduction
Image colorization is the process of adding color information to grayscale images. Autoencoders are a type of neural network that can learn to encode and decode data, and they have been successfully used for image colorization tasks. In this program, we utilize an autoencoder architecture with transfer learning, replacing the encoder section with the VGG16 model.

Transfer learning allows us to take advantage of pre-trained models, such as VGG16, which has been trained on a large dataset for image classification tasks. By using the pre-trained VGG16 model as a feature extractor, we can leverage its learned representations of image features to improve the quality of colorization.

## Installation
To run this program, you need to have the following dependencies installed:

- Python 3
- Jupyter Lab
- NumPy
- scikit-image
- TensorFlow
- Keras

You can install these dependencies using `pip` by running the following command:

```bash
pip install jupyterlab numpy scikit-image tensorflow keras
```

Once the dependencies are installed, you can clone the repository and navigate to the project directory:

```bash
git clone https://github.com/ayub1621/Image-Colorization.git
cd Image-Colorization
```

## Usage
1. Launch Jupyter Lab by running the following command in the project directory:
   ```bash
   jupyter lab
   ```

2. In Jupyter Lab, open the `Autoencoder Image Colorization & VGG.ipynb` notebook.

3. Follow the instructions in the notebook to load the pre-trained VGG16 model, prepare the dataset, and train the autoencoder with transfer learning.

4. Once the training is complete, you can use the trained model to colorize grayscale images by running the relevant code cells in the notebook.

## Results
The program aims to produce visually pleasing colorized images based on the input grayscale images. The quality of colorization depends on various factors, including the size and diversity of the training dataset, the architecture of the autoencoder, and the effectiveness of utilizing VGG16 as a feature extractor.

You can experiment with different hyperparameters, network architectures, and training strategies to improve the results. Additionally, you may consider using more advanced techniques, such as adversarial training or incorporating perceptual loss, to further enhance the colorization quality.
