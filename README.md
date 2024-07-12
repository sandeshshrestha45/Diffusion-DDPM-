# Diffusion-DDPM-

By leveraging the reverse diffusion process, DDPMs can create entirely new images that are not present in the original dataset. The model essentially learns the distribution of the data and can sample from this learned distribution to generate new, realistic images.

Training Phase: The model learns to predict the noise added to images from the dataset at various timesteps.
Sampling Phase: The model starts with a random noise image and iteratively denoises it to generate a new image.


Paper Link: https://arxiv.org/pdf/2006.11239 

Requirements:

torch == 2.3.1+cu118 <br>
torchvision ==  0.18.1+cu118

Ep0:
![alt text] (https://github.com/sandeshshrestha45/Diffusion-DDPM-/blob/main/ep0.png)

Ep100:
![alt text] (https://github.com/sandeshshrestha45/Diffusion-DDPM-/blob/main/ep100.png)

Ep800:
![alt text] (https://github.com/sandeshshrestha45/Diffusion-DDPM-/blob/main/ep800.png)

