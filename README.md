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
  <img width="1000" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/Taxonomy.PNG">
</p>

Taxonomy of colorization networks where classification of the colorization networks are based on structure, input, domain, and type of network. The details of each network used for single-image colorization using deep networks are reported in detail in our [paper](https://arxiv.org/pdf/2008.10774.pdf).

## Datasets
We compare the state-of-the-art algorithms on publicly available benchmark datasets which include Set5, Set14, BSD100, Urban100, DIV2K and
Manga109.
<p align="center">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_samples.png">
</p>
Representative test images from six super-resolution datasets used for comparing and evaluating algorithms

## Results

### Quantitative Results
<p align="center">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_results_table.png">
</p>

### Visual Results

<p align="center">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_results_fruit1.png">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_results_fruit2.png">
</p>

<p align="center">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_results_vegetables1.png">
  <img width="800" src="https://github.com/saeed-anwar/ColorSurvey/blob/master/Figs/NCD_results_vegetables2.png">
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


