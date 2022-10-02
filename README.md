# Diffusion model

Recently, denoising diffusion models, including score-based generative models, gained popularity as a powerful class of generative models, that can rival even generative adversarial networks (GANs) in image synthesis quality. They tend to generate more diverse samples, while being stable to train and easy to scale. Recent large diffusion models, such as DALL-E 2 and Imagen, have shown incredible text-to-image generation capability. One of their drawbacks is however, that they are slower to sample from, because they require multiple forward passes for generating an image.

Diffusion refers to the process of turning a structured signal (an image) into noise step-by-step. By simulating diffusion, we can generate noisy images from our training images, and can train a neural network to try to denoise them. Using the trained network we can simulate the opposite of diffusion, reverse diffusion, which is the process of an image emerging from noise.

## Stable Diffusion

Open source version of diffusion model

## Tensorflow version of Stable Diffusion

[Open on Google colab](https://colab.research.google.com/github/bikashkumars/stable-diffusion/blob/main/stable_diffusion_tensorflow.ipynb)
