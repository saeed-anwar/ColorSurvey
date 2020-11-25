# Image Colorization: A Survey and Dataset
This repository is for colorization survey introduced in the following paper

[Saeed Anwar](https://saeed-anwar.github.io/), Muhammad Tahir, Chongyi Li, Ajmal Mian, Fahad Shahbaz Khan, Abdul Wahab Muzaffar, "Image Colorization: A Survey and Dataset", [arXiv](https://arxiv.org/pdf/2008.10774.pdf), 2020


## Contents
1. [Introduction](#introduction)
2. [Overview](#overview)
3. [Datasets](#datasets)
4. [Results](#results)
5. [Citation](#citation)
6. [Acknowledgements](#acknowledgements)

## Introduction
Image colorization is an essential image processing and computer vision branch to colorize images and videos.  Recently, deep learning techniques progressed notably for image colorization. This article presents a comprehensive survey of recent state-of-the-art colorization using deep learning algorithms, describing their fundamental block architectures in terms of skip connections, input etc. as well as optimizers, loss functions, training protocols, and training data etc. Generally, we can roughly categorize the existing colorization techniques into seven classes. Besides, we also provide some additional essential issues, such as benchmark datasets and evaluation metrics.  We also introduce a new dataset specific to colorization and perform an experimental evaluation of the publicly available methods. In the last section, we discuss the limitations, possible solutions, and future research directions of the rapidly evolving topic of deep image colorization that the community should further address.

## Overview
An overview of the existing single-image colorization techniques are present below 

<p align="center">
  <img width="500" src="https://github.com/saeed-anwar/SRsurvey/blob/master/Figs/params_comp.PNG">
</p>

A diverse range of network architectures used for single-image colorization using deep networks in this [paper](https://arxiv.org/pdf/2008.10774.pdf).

## Datasets
We compare the state-of-the-art algorithms on publicly available benchmark datasets which include Set5, Set14, BSD100, Urban100, DIV2K and
Manga109.
![Images](/Figs/RepresentativeImages.PNG)
Representative test images from six super-resolution datasets used for comparing and evaluating algorithms

## Results
### Quantitative Results
![PSNR_SSIM_2x](/Figs/2xTable.PNG)
![PSNR_SSIM_3x](/Figs/3xTable.PNG)
![PSNR_SSIM_4x](/Figs/4xTable.PNG)
Mean PSNR and SSIM for the SR methods evaluated on the benchmark datasets. The ’-’ indicates that the method is not suitable to handle the images of the corresponding dataset.

![PSNR_SSIM_8x](/Figs/8xTable.PNG)
The results for 8x Super-resolution.

### Visual Results

![Visual_PSNR_SSIM_BI](/Figs/Urban.PNG)
Super-resolution qualitative comparison for CNN-SR algorithms for 4x and 8x
![Visual_PSNR_SSIM_BI](/Figs/SR_GAN.PNG)
Visual comparison for GAN-SR algorithms for 4x

## Ablation
![PARAMETERS_TABLE](/Figs/parameters.PNG)

Parameters comparison of CNN-based SR algorithms. GRL stands for Global residual learning, LRL means Local residual learning, MST is
abbreviation of Multi-scale training.


<p align="center">
  <img width="500" src="https://github.com/saeed-anwar/SRsurvey/blob/master/Figs/mult_adds_comp.PNG">
</p>
Comparison of Multiplication-Addition operations in various SR networks. Note that FLOPs are roughly double the number of mult-adds.
Algorithmic runtime (during inference) is proportional to the multi-add operations.

<p align="center">
  <img width="500" src="https://github.com/saeed-anwar/SRsurvey/blob/master/Figs/params_comp.PNG">
</p>
Comparison of number of parameters in various SR architectures. The memory footprint and training time of the model is directly related to the number of tunable parameters.

## Citation
If you find the code helpful in your resarch or work, please cite the following papers.
```
@article{anwar2020deepSR,
  author = {Anwar, Saeed and Khan, Salman and Barnes, Nick},
  title = {A Deep Journey into Super-Resolution: A Survey},
  year = {2020},
  issue_date = {June 2020},
  publisher = {Association for Computing Machinery (ACM)},
  address = {New York, NY, USA},
  volume = {53},
  number = {3}, 
  issn = {0360-0300},
  journal = {ACM Computing Surveys (ACMCSUR)},
  month = may,
  articleno = {60}, 
  numpages = {34},
}

@article{anwar2019drln,
  title={Densely Residual Laplacian Super-Resolution},
  author={Anwar, Saeed and Barnes, Nick},
  journal={arXiv preprint arXiv:1906.12021},
  year={2019}
}

```
## Acknowledgements


