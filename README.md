# Autodecoder-3D-Latent-Diffusion

A tiny implementation of autodecoder 3D latent diffusion in a python notebook. The autodecoder enables 2D supervised meta-learning for parameterizing 3D headphone objects from the publicly available ShapeNetCore dataset. After pre-training an autodecoder and NeRF rendering pipeline end-to-end, a random latent code is sampled and denoised via diffusion to yield a novel 3D object.
