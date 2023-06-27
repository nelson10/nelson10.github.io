---
title: "Multispectral Filter Array Design by Optimal Sphere Packing"
collection: publications
permalink: /publication/2022-11-09-Multispectral-filter-array
excerpt: 
date: 2023-06-11
venue: 'IEEE Transactions on Image Processing'
#paperurl: 'https://doi.org/10.1364/OE.444864'
#citation: 'Nelson Diaz, Alejandro Alvarado, Pablo Meza, Felipe Guzmán, and Esteban Vera, &quot;Multispectral Filter Array Design by Optimal Sphere Packing.&quot; <i>Opt. Express,</i>. vol. 30, pp. 887-901, 2023.'
---

Recommended citation: **N. Diaz**, A. Alvarado, P. Meza, F. Guzmán and E. Vera, "Multispectral Filter Array Design by Optimal Sphere Packing," <i> IEEE Transactions on Image Processing,</i> 2023. [[DOI]](https://ieeexplore.ieee.org/document/10163979),[[Paper]](https://nelson10.github.io/files/2023_IEEE_TIP.pdf), [[TechRxiv]](https://doi.org/10.36227/techrxiv.21502899.v1), [[Code]](https://github.com/nelson10/DemosaickingMultispectral3DSpherePacking.git).

Multispectral Imaging (MSI) collects a datacube of spatio-spectral information of a scene. Many acquisition methods for spectral imaging use scanning, preventing its widespread usage for dynamic scenes. On the other hand, the conventional color filter array (CFA) method often used to sample color images has also been extended to snapshot MSI using a Multispectral Filter Array (MSFA), which is a mosaic of selective spectral filters placed over the Focal Plane Array (FPA). However, even state-of-the-art MSFAs coding patterns produce artifacts and distortions in the reconstructed spectral images, which might be due to the non-optimal distribution of the spectral filters. To reduce the appearance of artifacts and provide tools for the optimal design of MSFAs, this paper proposes a novel mathematical framework to design MSFAs using a Sphere Packing (SP) approach. By assuming that each sampled filter can be represented by a sphere within the discrete datacube, SP organizes the position of the equal-size and disjoint spheres’s centers in a cubic container. Our method is denoted Multispectral Filter Array by Optimal Sphere Packing (MSFA-OSP), which seeks filter positions that maximize the minimum distance between the spheres’s centers. Simulation results show an image quality improvement of up to 2 dB and a remarkable boost in spectral similarity when using our proposed MSFA design approach for a variety of reconstruction algorithms. Moreover, MSFA-OSP notably reduces the appearance of false colors and zipper effect artifacts, often seen when using state-of-the-art demosaicking algorithms. Experiments using synthetic and real data prove that the proposed MSFA-OSP outperforms state-of-the-art MSFAs in terms of spatial and spectral fidelity.


### Cite

```
@ARTICLE{10163979,
  author={Diaz, Nelson and Alvarado, Alejandro and Meza, Pablo and Guzmán, Felipe and Vera, Esteban},
  journal={IEEE Transactions on Image Processing}, 
  title={Multispectral Filter Array Design by Optimal Sphere Packing}, 
  year={2023},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TIP.2023.3288414}}
```
<a href="https://www.scimagojr.com/journalsearch.php?q=25534&amp;tip=sid&amp;exact=no" title="SCImago Journal &amp; Country Rank"><img border="0" src="https://www.scimagojr.com/journal_img.php?id=25534" alt="SCImago Journal &amp; Country Rank"  /></a>
