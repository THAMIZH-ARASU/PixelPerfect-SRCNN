
# Image Enhancing Using SRCNN

Welcome to the **Image Enhancing Using Super-Resolution Convolutional Neural Network (SRCNN)** project! This repository demonstrates the power of deep learning to enhance image quality, converting low-resolution images into high-resolution masterpieces.

---

## Table of Contents

- [Image Enhancing Using SRCNN](#image-enhancing-using-srcnn)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Installation](#installation)
  - [How to Use](#how-to-use)
  - [Results](#results)
  - [Acknowledgments](#acknowledgments)
  - [License](#license)

---

## Overview

The SRCNN algorithm revolutionizes single-image super-resolution (SR) by leveraging deep convolutional neural networks. It maps low-resolution images to their high-resolution counterparts with improved clarity and detail. This implementation includes:

- **Key Metrics**: Evaluate the performance using PSNR, MSE, and SSIM.
- **Color Space Conversion**: Pre-processing in YCrCb space to focus on luminance (Y-channel).
- **Image Processing with OpenCV**: Advanced handling of images for preparation and output.

---

## Installation

To run this notebook, ensure the following prerequisites are installed:
- Python 3.8+
- TensorFlow/Keras
- OpenCV
- NumPy
- Matplotlib

Install the required dependencies with:
```bash
pip install -r requirements.txt
```

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/THAMIZH-ARASU/PixelPerfect-SRCNN.git
   ```
2. Open the notebook:
   ```bash
   jupyter notebook ImageEnhancingUsingSRCNN.ipynb
   ```
3. Follow the steps in the notebook to load, preprocess, and enhance your images.

---

## Results

Below is an example of an image enhanced using SRCNN:

![Enhanced Image](output\Odie256B.png)

---

## Acknowledgments

This project is inspired by the paper [*Image Super-Resolution Using Deep Convolutional Networks*](https://arxiv.org/abs/1501.00092) by Chao Dong and colleagues. Special thanks to the creators of OpenCV and TensorFlow/Keras.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
