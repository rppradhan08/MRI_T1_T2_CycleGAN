![GitHub Repo stars](https://img.shields.io/github/stars/rppradhan08/MRI_T1_T2_CycleGAN)
![GitHub forks](https://img.shields.io/github/forks/rppradhan08/MRI_T1_T2_CycleGAN?color=green)
![contributors-shield](https://img.shields.io/github/contributors/rppradhan08/MRI_T1_T2_CycleGAN)
[![LinkedIn][linkedin-shield]](https://in.linkedin.com/in/raj-praveen-pradhan-306625101)

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555

<p align="center">
  <a href="https://github.com/rppradhan08/MRI_T1_T2_CycleGAN">
    <img src="https://github.com/rppradhan08/MRI_T1_T2_CycleGAN/blob/main/cyclegan.gif" alt="Logo" width="650px" height="225px">
  </a>
  <br>
  <br>
  <h1>MRI T1-T2 CyclicGAN</h1>
</p>

## Table of Contents

- [About the Project](#about-the-project)
  - [Approach](#approach)
  - [Steps Involved](#steps-involved)
- [Getting Started](#getting-started)
  - [Installations](#installations)
  - [Loading images and data preparation for the CNN classifier](#loading-images-and-data-preparation-for-the-cnn-classifier)
  - [Building and training CNN classifier](#building-and-training-cnn-classifier)
  - [Evaluating the CNN Classifier](#evaluating-the-cnn-classifier)
  - [Capturing video frames and detecting faces](#capturing-video-frames-and-detecting-faces)
  - [Performing perdictions and displaying results](#performing-perdictions-and-displaying-results)
- [Contacts](#contacts)
# About The Project
This project uses unpaired dataset consisting of TN1 and TN2 MRI scans of brain to train a deep learning model to convert TN1 into TN2 scans and vice-versa. [CycleGAN](https://junyanz.github.io/CycleGAN/) technique have been used for the unpaired image translation application.


