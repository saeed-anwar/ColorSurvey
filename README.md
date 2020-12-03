# Image Colorization: A Survey and Dataset
This repository is for colorization survey introduced in the following paper

[Saeed Anwar](https://saeed-anwar.github.io/), Muhammad Tahir, Chongyi Li, Ajmal Mian, Fahad Shahbaz Khan, Abdul Wahab Muzaffar, "Image Colorization: A Survey and Dataset", [arXiv](https://arxiv.org/pdf/2008.10774.pdf), 2020

---

## Contents
1. [Introduction](#introduction)
2. [Overview](#overview)
3. [Datasets](#datasets)
4. [Results](#results)
5. [Citation](#citation)
6. [Acknowledgements](#acknowledgements)

## Introduction
Image colorization is an essential image processing and computer vision branch to colorize images and videos.  Recently, deep learning techniques progressed notably for image colorization. This article presents a comprehensive survey of recent state-of-the-art colorization using deep learning algorithms, describing their fundamental block architectures in terms of skip connections, input etc. as well as optimizers, loss functions, training protocols, and training data etc. Generally, we can roughly categorize the existing colorization techniques into seven classes. Besides, we also provide some additional essential issues, such as benchmark datasets and evaluation metrics.  We also introduce a new dataset specific to colorization and perform an experimental evaluation of the publicly available methods. In the last section, we discuss the limitations, possible solutions, and future research directions of the rapidly evolving topic of deep image colorization that the community should further address.

---

## Overview
An overview of the existing single-image colorization techniques are present below 

<p align="center">
  <img width="1000" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/Taxonomy.PNG">
</p>

Taxonomy of colorization networks where classification of the colorization networks are based on structure, input, domain, and type of network. The details of each network used for single-image colorization using deep networks are reported in detail in our [paper](https://arxiv.org/pdf/2008.10774.pdf).

---

## Datasets
We aim to remove this unrealistic setting for image colorization by collecting images that are true to their colors. For example, a carrot will have an orange
color in most images. Bananas will be either greenish or yellowish. We have collected 723 images from the internet distributed in 20 categories. Each image has an object and
a white background. We name our dataset as Natural-Color Dataset (NCD). The following figures shows representative test images for each category from our proposed Natural-Color dataset (NCD).

<p align="center">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_samples.png">
</p>

***Our NCD dataset [GrayScale](https://drive.google.com/file/d/1GpmEVNFn12bK0EoXK46FP3cXFUosomaG/view?usp=sharing)***

***Our NCD dataset [Color-Groundtruth](https://drive.google.com/file/d/1k_UvYzdrHbphW4UcbDb9jWB0ZQIAGEAo/view?usp=sharing)***
---
**State-of-the-art method results**

***[AutomaticColorizer](https://drive.google.com/file/d/1DUG3syZ9xceMe3baBBOAEeldE26zCq7R/view?usp=sharing)***

***[ColorCapsNet](https://drive.google.com/file/d/10E47p5jIjiP5_Iab2GJkCWk6OBhkrTKD/view?usp=sharing)***

***[ColofulColorization](https://drive.google.com/file/d/15dXx8UBVMa9SwFXqkljha6eChrMA6m6q/view?usp=sharing)***

***[InstanceAwareColorization](https://drive.google.com/file/d/1BbddVt6UAuRR3-Fgoy8JvOpPyrCAVzRA/view?usp=sharing)***

***[LetBeColor](https://drive.google.com/file/d/1DcU1ub-wiQf4yNHa_E3rrk9swT4cKaKY/view?usp=sharing)***

***[RealTimeUserGuided](https://drive.google.com/file/d/1ORPxVU9DhevOCWpK0UfpBFCDPc2NSuz8/view?usp=sharing)***

---
## Results

### Quantitative Results

Comparisons of the state-of-the-art methods for the colorization in terms of PSNR, SSIM, PCQI, and IQM on our Natural-Color Dataset. The higher value of the metrics indicates better performance.

<p align="center">
  <img width="1000" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_results_table.png">
</p>

### Visual Results
Visual comparison of colorization algorithms on different fruit images from the Natural-Color Dataset. State-of-the-art colorization algorithms are unable to colorize the images effectively.

<p align="center">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_results_fruit1.png">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_results_fruit2.png">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/refs.png">
</p>


Qualitative comparison on a few sample images of vegetables from Natural-Color Dataset. Most of the algorithms fail to reproduce the original colors.
<p align="center">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_results_vegetables1.png">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_results_vegetables2.png">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/refs.png">
</p>

## Citation
If you find the code helpful in your resarch or work, please cite the following papers.
```
@article{anwar2020ColorSurvey,
  title={Image Colorization: A Survey and Dataset},
  author={Anwar, Saeed and Tahir, Muhammad and Li, Chongyi and Mian, Ajmal and Khan, Fahad Shahbaz and Muzaffar, Abdul Wahab},
  journal={arXiv preprint arXiv:2008.10774},
  year={2020}
}
```
## Acknowledgements


