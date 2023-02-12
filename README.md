Our attempt in accelerating the generation time of an image using denoising diffusion probalistic models. 
We reduce the computation time by using smaller neural networks when generating highly noisy images, at the beginning of the diffusion process. 
As the process progresses and the images get less noisy, we add more layers to the neural network in order to get better denoising diffusion results.

Our code is based on the code presented on the paper [Denoising Diffusion Implicit Models](https://arxiv.org/abs/2010.02502), and the original
code can be found here: [ddim code](https://github.com/ermongroup/ddim). 

For further explanation and our results please refer to [Accelerating Diffusion Models](https://github.com/shellymeir/Diffusion-Models-Acceleration/blob/main/Accelaration_diffusion.pdf)
