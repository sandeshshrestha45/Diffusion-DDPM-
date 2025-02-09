# Diffusion-DDPM-

By leveraging the reverse diffusion process, DDPMs can create entirely new images that are not present in the original dataset. The model essentially learns the distribution of the data and can sample from this learned distribution to generate new, realistic images.

Training Phase: The model learns to predict the noise added to images from the dataset at various timesteps.
Sampling Phase: The model starts with a random noise image and iteratively denoises it to generate a new image.


Paper Link: https://arxiv.org/pdf/2006.11239 

Requirements:

torch == 2.3.1+cu118 <br>
torchvision ==  0.18.1+cu118


Ep0:
![ep0](https://github.com/user-attachments/assets/ecfd9dcc-db1b-4b72-890c-f8110603e65a)

Ep100:
![ep400](https://github.com/user-attachments/assets/02c77464-702b-49c0-bc8d-098cf1b09737)

Ep800:
![ep800](https://github.com/user-attachments/assets/ea487dad-9b13-4745-aa66-25314971e324)


