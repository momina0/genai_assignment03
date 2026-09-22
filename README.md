# Generative Adversarial Networks: Image Translation & Mode Collapse

Three GAN experiments implemented in PyTorch, each with a Gradio demo.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![Gradio](https://img.shields.io/badge/Gradio-F97316?logo=gradio&logoColor=white)

| Notebook | What it covers |
|---|---|
| `Pix2Pix_Image_Translation.ipynb` | **Paired** image-to-image translation with a U-Net generator and PatchGAN discriminator |
| `CycleGAN_Domain_Adaptation.ipynb` | **Unpaired** sketch to photo translation with ResNet generators and adversarial (LSGAN), cycle-consistency and identity losses. Evaluated with PSNR/SSIM |
| `GAN_Mode_Collapse.ipynb` | Reproduces **mode collapse** in a DCGAN and mitigates it with **WGAN-GP** (gradient penalty) |

Each notebook includes loss curves, sample grids and quantitative evaluation.
