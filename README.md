# SequentialArt_StableDiffusion
# Text-to-Image and Image-to-Image Generation using Diffusion Models

This repository contains code for generating images from text descriptions and modifying existing images based on provided prompts using diffusion models. The process involves denoising an initial image representation guided by a text prompt.

## Note
Ensure that you have the necessary GPU resources available for faster processing, as the models are optimized for GPU usage.
On Google Colab, I used a T4 GPU to run this code, which was sufficient enough.
This README provides clear instructions on how to install the required packages, use the provided code for both text-to-image and image-to-image generation, and includes additional notes for efficient usage.


## Installation

Ensure you have the necessary packages installed. You can install them via pip:

```bash
!pip install --upgrade diffusers accelerate transformers
