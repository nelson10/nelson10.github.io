---
title: "Adaptive Multisensor Acquisition via Spatial Contextual Information for Compressive Spectral Image Classification"
excerpt: "This repository aims to adaptive design the coded apertures from compressive spectral images acquired with a multisensor camera. The classification is performed using the captured compressive projections.
<br/><img src='/images/twoArms.png'>"
collection: portfolio
---

This repository contains the code to reproduce the results presented in the paper following paper:

*N. Diaz, J. M. Ramirez, E. Vera and H. Arguello, "Adaptive Multisensor Acquisition via Spatial Contextual Information for Compressive Spectral Image Classification," in IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, doi: 10.1109/JSTARS.2021.3111508.

[GitHub Repository](https://github.com/nelson10/CompressiveAdaptiveClassificationMultisensor..git)

## Usage

This code was written using Matlab R2020b. It should be downloaded the CompressiveAdaptiveClassificationMultisensor repository
1. Download this repository via git 
```
git clone https://github.com/nelson10/CompressiveAdaptiveClassificationMultisensor.git
```
2. To run the code using either the function Main3DCASSI or MainCCASSI that performs the sensing, Adaptive coded aperture design, and classification using the compressive measurements.


## Datasets

The datasets could be download from the following [link](http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes) and [link](https://ieee-dataport.org/documents/hen-datacube-ground-truth)

The files should be placed in the Data folder of this repository.

If you use this code or dataset Hen_FullSpectral.mat, please consider citing our paper with the following Bibtex code:

```
@ARTICLE{9534664,
  author={Diaz, Nelson and Ramirez, Juan and Vera, Esteban and Arguello, Henry},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  title={Adaptive Multisensor Acquisition via Spatial Contextual Information for Compressive Spectral Image Classification}, 
  year={2021},
  volume={14},
  number={},
  pages={9254-9266},
  doi={10.1109/JSTARS.2021.3111508}}
```

The published version is available at this [link](https://ieeexplore.ieee.org/document/9534664)

## Abstract

Spectral image classification uses the huge amount of information provided by spectral images to identify objects in the scene of interest. In this sense, spectral images typically contain redundant information that is removed in later processing stages. To overcome this drawback, compressive spectral imaging (CSI) has emerged as an alternative acquisition approach that captures the relevant information using a reduced number of measurements. Various methods that classify spectral images from compressive projections have been recently reported whose measurements are captured by non-adaptive, or adaptive schemes discarding any contextual information that may help to reduce the number of captured projections. In this paper, an adaptive compressive acquisition method for spectral image classification is proposed. In particular, we adaptively design coded aperture patterns for a dual-arm CSI acquisition architecture, where the first system obtains compressive multispectral projections and the second arm registers compressive hyperspectral snapshots. The proposed approach exploits the spatial contextual information captured by the multispectral arm to design the coding patterns such that subsequent snapshots acquire the scene's complementary information improving the classification performance. Results of extensive simulations are shown for two state-of-the-art databases: Pavia University and Indian Pines. Furthermore, an experimental setup that performs the adaptive sensing was built to test the performance of the proposed approach on a real data set. The proposed approach exhibits superior performance with respect to other methods that classify spectral images from compressive measurements.
