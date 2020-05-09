# VAE-for-Collaborative-Filtering-Pytorch
Implementation of 'Variational Autoencoders for Collaborative Filtering' paper [https://arxiv.org/abs/1802.05814]  in Pytorch

This repository include:
 1. Data Processing
 2. Denoising AutoEncoder Model in the paper
 3. Validation for the model
 4. Model Ablation Studies:
    a. Exlplicit Use of l2 norm for model weights
    b. Effect of dropout
    
Dependency: Python3

Simply run the git_main.ipynb

Validation Study for the Models:

![](images/combine.png)


Final: Model with explicit l2 loss
no_l2 : Model without explicit l2 loss
no_drop: Model without dropout. It overfits as expected.

To DO:
1. Clean up the code
2. Add VAE model
3. Add test matrix in the code

Note: Data preparation is mostly based on original implementation [source](https://github.com/dawenl/vae_cf) with some changes.
