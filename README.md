![GitHub Repo stars](https://img.shields.io/github/stars/rppradhan08/MRI_T1_T2_CycleGAN)
![GitHub forks](https://img.shields.io/github/forks/rppradhan08/MRI_T1_T2_CycleGAN?color=green)
![contributors-shield](https://img.shields.io/github/contributors/rppradhan08/MRI_T1_T2_CycleGAN)
[![LinkedIn][linkedin-shield]](https://in.linkedin.com/in/raj-praveen-pradhan-306625101)

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555

<p align="center">
  <a href="https://github.com/rppradhan08/MRI_T1_T2_CycleGAN">
    <img src="https://github.com/rppradhan08/MRI_T1_T2_CycleGAN/blob/main/cyclegan.gif" alt="Logo" width="650px" height="225px">
  </a>
</p>
<br>
<h1 align="center">MRI T1-T2 CyclicGAN</h1>

## Table of Contents
- [Description](#description)
  - [About Image translation](#about-image-translation)
    - [Read more](#read-more)

# Description

This project uses unpaired dataset consisting of TN1 and TN2 MRI scans of brain to train a deep learning model to convert TN1 into TN2 scans and vice-versa. [CycleGAN](https://junyanz.github.io/CycleGAN/) technique have been used for the purpose of [unpaired image to image translation](https://arxiv.org/abs/1703.10593).

## About Image translation

Image-to-image translation is a class of vision and graphics problems where the goal is to learn the mapping between an input image and an output image using a training set of aligned image pairs. However, for many tasks, paired training data will not be available.

### Read more

- [Unpaired image to image translation using CyclicGAN](https://arxiv.org/abs/1703.10593)
- [Style Transfer vs Cyclic Gan](https://leolaugier.wp.imt.fr/2019/09/09/style-transfer-in-computer-vision-image-to-image-translation/)
