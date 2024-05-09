# Advanced Generative Modeling for Skin Lesion Images

## Introduction
The objective is to efficiently encode and decode high-dimensional image data while capturing meaningful latent representations using a Vector-Quantized Variational Autoencoder (VQ-VAE). Additionally, an Auto Regressive Model is trained to generate new, realistic images based on the learned latent space representations.ISIC dataset is used here.

## Experiments
### Experiment 1: Data Pre-processing
- Apply normalization and four different types of relevant data transformations of your choice to pre-process the input data.

### Experiment 2: Phase 1 - VQ-VAE
- Design a VQ-VAE network using CNN encoder and decoder modules to learn a quantized latent space using a codebook.

### Experiment 3: Phase 2 - Auto Regressive Model
- Design and train an Auto Regressive Model (PixelCNN, MADE, GatedCNN) to generate diverse realistic images using the codebook and the decoder trained during phase 1.

### Experiment 4: Inference Function
- Define an inference function to showcase the generated samples during demonstration.

## How to Use
1. Clone this repository.
2. Download the ISIC dataset and place it in the `data/` directory.
3. Run the training script `main.ipynb` to train the VQ-VAE and Auto Regressive Model.

