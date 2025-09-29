# Pistachio-Image-Synthesis-using-a-Generative-Adversarial-Network

Pistachio Image Synthesis using a Generative Adversarial Network (GAN)

Project Overview

This project explores the domain of generative modeling by developing a Deep Convolutional Generative Adversarial Network (DCGAN) to synthesize realistic images of pistachios. The focus was not only on image generation but also on a critical analysis of the GAN's training process and common challenges.

A comparative study was conducted on three different GAN architectures:
1.  A **Baseline DCGAN**.
2.  A **Manually Modified DCGAN** with an increased number of filters.
3.  A **Hyperparameter-Tuned DCGAN**, optimized using the KerasTuner library.

The quality and diversity of the generated images were quantitatively evaluated using the **Fréchet Inception Distance (FID)** score.

Technologies Used
- Python
- TensorFlow / Keras
- KerasTuner
- NumPy
- Matplotlib

Dataset
The project uses the **Pistachio Image Dataset** as the basis for training the GAN to generate new, similar images.

How to Run this Project
1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/geraldusjeremy/Pistachio-Image-Synthesis-using-a-Generative-Adversarial-Network.git](https://github.com/geraldusjeremy/Pistachio-Image-Synthesis-using-a-Generative-Adversarial-Network.git)
