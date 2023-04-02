### Contains implementation of all model architectures used in stable diffusion

Data - Prepare, process and load data from Imagenet, and LSUN datasets

Models - 
  diffusion - 
    dpm_solver - No idea what it does.
    classifier.py - Noisy latent image classifier. Not sure how it is used for diffusion exactly. Perhaps, it was used for conducting ablation studies with classifier based guidance.
    ddim/ddpm/plms - different implementations of the sampling process for diffusion.
    
  autoencoder.py - Implementation of autoencoders (VQVAEs and Autoencoder_KL class)
  
Modules - 
  diffusionmodules - Implementation of stable diffusion models (base and open AI)
  distributions - Implementation of DIRAC distribution and Diagonal Gaussian Distribution
  encoders-
      modules.py - NLP embeddings code using BERT etc.
  image_degradation - Super resolution model implementation https://github.com/cszn/BSRGAN/
  loss - various loss implementation for vqgan etc.
  

  
