---

# Archived

This repo is now archived to due lack of interest on my part, and the fact that it no longer runs on my hardware or Google Cloud, so I can't use or test it anyways. However, as far as I know, this all should work fine in its current state.

---

[![Open AUTOMATIC1111 in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/askiiart/universal-fast-stable-diffusion/blob/main/fast_stable_diffusion_AUTOMATIC1111.ipynb) [![Lint Code Base](https://github.com/askiiart/universal-fast-stable-diffusion/actions/workflows/linter.yml/badge.svg)](https://github.com/askiiart/universal-fast-stable-diffusion/actions/workflows/linter.yml)

# Original README:

## fast-stable-diffusion Colabs, +25-50% speed increase, AUTOMATIC1111 + DreamBooth
Colab adaptations AUTOMATIC1111 Webui and Dreambooth, train your model using this easy simple and fast colab, all you have to do is enter you huggingface token once, and it will cache all the files in GDrive, including the trained model and you will be able to use it directly from the colab, make sure you use high quality reference pictures for the training, enjoy !!
 
 
<center><b>&nbsp;&nbsp;	&nbsp;	&nbsp;	&nbsp;	&nbsp;&nbsp;	&nbsp;	&nbsp;	&nbsp;	&nbsp;&nbsp;	&nbsp;	&nbsp;	&nbsp;	&nbsp;&nbsp;	&nbsp;	&nbsp;	&nbsp;	&nbsp;&nbsp;	&nbsp;	&nbsp;	&nbsp;	&nbsp;&nbsp;	&nbsp;	&nbsp;AUTOMATIC1111 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DreamBooth
 
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://colab.research.google.com/github/askiiart/universal-fast-stable-diffusion/blob/main/fast_stable_diffusion_AUTOMATIC1111.ipynb">
<img src='https://github.com/askiiart/universal-fast-stable-diffusion/raw/main/Dreambooth/1.jpg'></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://colab.research.google.com/github/askiiart/universal-fast-stable-diffusion/blob/main/fast-DreamBooth.ipynb"><img src='https://github.com/askiiart/universal-fast-stable-diffusion/raw/main/Dreambooth/4.jpg'></a>

Dreambooth paper : https://dreambooth.github.io/
version
SD implementation by @XavierXiao : https://github.com/XavierXiao/Dreambooth-Stable-Diffusion
 
### Other Webuis
 
<b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HLKY &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Relaxed mode
 
<a href="https://colab.research.google.com/github/askiiart/universal-fast-stable-diffusion/blob/main/fast_stable_diffusion_hlky.ipynb"><img src='https://github.com/askiiart/universal-fast-stable-diffusion/raw/main/Dreambooth/2.jpg'> </a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://colab.research.google.com/github/askiiart/universal-fast-stable-diffusion/blob/main/fast_stable_diffusion_relaxed.ipynb"> 
 <img src='https://github.com/askiiart/universal-fast-stable-diffusion/raw/main/Dreambooth/3.jpg'></a>
</center>

---

# README Additions
This is a universal fork of TheLastBen's [fast-stable-diffusion](https://github.com/TheLastBen/fast-stable-diffusion) repository.
repository, but is universal (for Linux). I'll keep the AUTOMATIC1111 notebook working for sure, but no promises about the others.

## Notes and Limitations 
- **Only universal on Linux**, only `Local_fast_DreamBooth-Win.iypnb` is Windows compatible (and is *only* compatible with Windows). And IDK about Mac, but I don't think anyone cares about Mac anyways.
- Sorry for no updates in a while, [my drivers were broken](https://www.youtube.com/watch?v=i2lhwb_OckQ).

## TODO:
- Remove localtunnel - not needed, and doesn't work properly on local runtimes
