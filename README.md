# ConditionalGAN

## Overview

This repository contains the implementation of a Conditional Deep Convolutional Generative Adversarial Network (DCGAN) trained on the MNIST dataset to generate high-quality, state-of-the-art handwritten digits. The network was trained using my personal RTX 4060Ti GPU, and the results speak for themselves. With 300 epochs of training, the Conditional DCGAN achieves remarkable fidelity in the generated images, closely mirroring the real MNIST digits.

![output_300](https://github.com/user-attachments/assets/925932db-3760-4f4a-87a2-5f488525a289)

## Features

- **Conditional DCGAN:** The model is conditioned on the digit class, allowing for the generation of specific digit types.
- **High Fidelity:** The generated images demonstrate high visual quality and closely match the corresponding real digits.
- **Pre-trained Checkpoints:** Trained checkpoints for 300th epoch are provided, enabling you to either continue training or directly use the model for inference.
- **Customizable:** The architecture and training process are easily modifiable, allowing experimentation with different datasets or hyperparameters.

## Getting Started

### Prerequisites

Ensure you have the following dependencies installed:

- Python 3.9-3.11
- PyTorch
- torchvision
- matplotlib

You can install the required packages using pip:

```bash
pip install torch torchvision matplotlib
```

### Clone the Repository

```bash
git clone https://github.com/inventwithdean/ConditionalGAN.git
cd ConditionalGAN
```


### Results

The generated digits after 300 epochs show a remarkable similarity to the real MNIST digits. You can view a comparison between true and generated images in `outputs/output_300.png`.

## Checkpoints

- Trained model checkpoints for 300th epoch are available in the root directory.

## Acknowledgements

This project was trained and developed using my personal RTX 4060Ti GPU. The implementation is based on the original DCGAN paper with little modifications in kernel sizes and it of course includes modifications to incorporate conditional generation.

## License

This project is licensed under the MIT License.
