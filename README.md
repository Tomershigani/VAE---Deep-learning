# VAE-Deep-Learning-with-Continuous-and-Discrete-Latent-Spaces

In this project, I have implemented three Variational Autoencoder (VAE) models with different latent spaces.
Specifically, I created a VAE with a continuous latent space using a Gaussian distribution, a VAE
with a discrete latent space using Gumbel-Softmax, and a VAE with both continuous and discrete latent spaces.

To test these models, I used the MNIST dataset and randomly colored each sample with a different color. By doing so,
I aimed to show that VAEs can be applied not only to grayscale images but also to colored ones.

I used PyTorch to implement the VAE models and trained them using the MNIST dataset. Then, I generated images from the models' latent spaces 
and visualized them. I also compared the reconstructions and the interpolation results of the three VAE models.

Overall, this project demonstrates the flexibility and power of VAEs in handling different types of data 
and in capturing complex latent spaces.

<img src="https://user-images.githubusercontent.com/81327428/221796768-c403e4cb-64d9-419f-b029-718cd4cd47a6.png" width="200" height="200">     <img src="https://user-images.githubusercontent.com/81327428/221796877-df58233b-3cf0-46c2-993f-7e0c21c323d4.png" width="200" height="200">     <img src="https://user-images.githubusercontent.com/81327428/221797592-3f4a2ac1-d22f-4f85-aef3-407057415351.png" width="350" height="200">
