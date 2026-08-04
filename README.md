# Representation Learning and Generative Modeling for Faces

## Overview

This project focuses on learning facial representations for verification and generating face images using deep learning models. The work explores two major problems:

1. Face verification using metric learning with Siamese Networks  
2. Face generation using GANs and Conditional GANs  

---

## Face Verification using Siamese Network

- Used the **Labeled Faces in the Wild (LFW)** dataset.
- Trained a Siamese network to learn similarity between face embeddings.
- Compared different optimizers
- Tested multiple learning-rate scheduling strategies.
---

## Face Generation using GANs

### Approach
- Implemented a GAN with:
  - A generator network to create face images from random latent vectors.
  - A discriminator network to distinguish real and generated images.
- Extended the model to a Conditional GAN (cGAN) for controlled face generation.
