# vae-implementation
A TensorFlow implementation of Variational Autoencoder (VAE) for image reconstruction and latent space visualization on the MNIST dataset. 
## Image Generator using VAE
An end-to-end Generative AI implementation of a Variational Autoencoder (VAE) to learn latent representations and generate synthetic handwritten digits using the MNIST dataset.
## Project Overview
This project focuses on building an Encoder-Decoder architecture using unsupervised learning. The encoder maps input handwritten digits into a lower-dimensional bottleneck (latent space), while the decoder learns to reconstruct the images from this representation.
* **Framework:** TensorFlow 2.x
* **Dataset:** MNIST Dataset (accessed via TensorFlow's built-in module)
* **Architecture:** Convolutional Neural Network (Conv2D layers) with a 2-dimensional latent space
* **Training Details:** 10 epochs, batch size of 64, optimized via the Adam Optimizer
## Repository Structure
* **Code.ipynb:** Jupyter notebook containing data preprocessing, VAE architecture design, custom loss functions (Reconstruction Loss + KL Divergence), training loop, and evaluation.
* **Project Report.pdf:** The comprehensive project report outlining the structural design, executive summary, and methodology details.
* **results/:** Directory containing 10 pairs of original MNIST images alongside their corresponding VAE-reconstructed outputs.
## Results and Discussion
The Variational Autoencoder successfully performs reconstruction tasks by capturing the primary, macro structures of the target digits.
## Software Required:
* Python 3.x
* TensorFlow 2.x
* NumPy
* Matplotlib
* Jupyter Notebook
