# Data-Augmentation-Neural Style Transfer and GAN Project

## Overview

This project delves into the application of Neural Style Transfer and Generative Adversarial Networks (GANs).

## Techniques Used

### Neural Style Transfer

Neural Style Transfer is employed to blend the content of one image with the artistic style of another. Key features of Neural Style Transfer include:

- **Content Image:** The input image whose content will be retained in the final stylized output.
- **Style Image:** The reference image whose artistic style will be applied to the content image.
- **Loss Functions:** Content loss measures the difference in content between the input and output images, while style loss captures the differences in artistic style.

### Generative Adversarial Networks (GANs) 

Generative Adversarial Networks are utilized to generate novel images and enhance the model's ability to understand and reproduce complex patterns. The GAN architecture comprises two main components:
The GAN model undergoes adversarial training in an iterative process:

1. **Generator Training:** Aims to produce synthetic images that can deceive the discriminator.
2. **Discriminator Training:** Learns to distinguish between real and generated images.
3. **Adversarial Training:** Generator and discriminator are trained in tandem, each improving and adapting to the other.

## Requirements

- TensorFlow, numpy, IPython, matplotlib
