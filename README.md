<div align="center">

# Addressing Data Scarcity in Medical Imaging: A Latent Diffusion Approach to Synthetic Tumor Generation

[Anant Jamuar](mailto:jamuaranant@ieee.org)<sup>1</sup>, [Nikhil Verma](mailto:nikhilv129@gmail.com)<sup>2</sup>, [Sarisha P Sharma](mailto:sarishasharma01@gmail.com)<sup>1</sup>, [Dr. Mangala Gowri S G](mailto:mangalagowri_ece@sirmvit.edu)<sup>1 </sup>

<sup>1</sup>Department of Electronics and Communication Engineering, </br>Sir M Visvesvaraya Institute of Technology, Bengaluru, India

<sup>2</sup>Department of Information Science and Engineering, </br>Sir M Visvesvaraya Institute of Technology, Bengaluru, India

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Framework-orange)](https://pytorch.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

</div>

## Abstract
A major challenge in the field of medical image analysis is the data scarcity of high-fidelity medical images. The application of Latent Diffusion Models (LDM) in this field has shown significant ability in the synthesis of high-fidelity images and presents a promising solution to the problems of conventional data augmentation. In this project, we explore an application of LDM based generative modelling for medical image synthesis, using 2D Brain Slices as a demonstrative example. We preprocess FLAIR volumes from the BraTS 2020 dataset into normalized two-dimensional axial slices and train a KL-regularized autoencoder to learn latent representations. Furthermore, a U-Net diffusion model is trained in this latent space to effectively capture complex anatomical details. The generated MRI slices show visual fidelity and anatomical plausibility commensurate with the capabilities of latent diffusion models in the field of medical imaging. Consistent with the existing literature, the findings confirm that latent diffusion models can efficiently encode complex pathological patterns in a reduced latent space, thus reiterating their appropriateness as a general-purpose generative framework for healthcare imaging research.
