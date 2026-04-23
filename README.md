# DCGAN on MNIST Digits

## Overview
This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) on the MNIST dataset to generate synthetic handwritten digits from random noise.

## Problem Statement
MNIST is a standard benchmark for generative modelling. This project demonstrates how GANs can learn simple image distributions and produce new digit-like images.

## Objectives
- Train a DCGAN model on handwritten digit images
- Visualise generated outputs across training epochs
- Understand generator-discriminator dynamics
- Evaluate qualitative image quality improvements over time

## Dataset
MNIST contains grayscale images of handwritten digits from 0 to 9.

## Methodology
- Loaded and normalised the MNIST dataset
- Built generator and discriminator models
- Trained the DCGAN using adversarial loss
- Saved generated digit samples and model outputs

## Tech Stack
Python, TensorFlow/Keras or PyTorch, NumPy, matplotlib, Jupyter Notebook

## Results
Add:
- generated digit image grids
- training loss plots
- short explanation of how outputs improved over epochs

## Repository Structure
- notebooks/dcgan_mnist_training.ipynb
- images/
- outputs/
- requirements.txt

## How to Run
1. Clone the repository
2. Install dependencies
3. Run the notebook

## Key Learnings
This project helped build understanding of GAN fundamentals, adversarial loss behaviour, and image generation from latent vectors.

## Future Improvements
- Compare vanilla GAN vs DCGAN
- Add quantitative evaluation
- Train on Fashion-MNIST for a harder task
