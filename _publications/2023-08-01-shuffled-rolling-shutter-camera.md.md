---
title: "Multispectral Filter Array Design by Optimal Sphere Packing"
collection: publications
permalink: /publication/2023-06-26-Multispectral-filter-array
excerpt: 
date: 2023-06-26
venue: 'IEEE Transactions on Image Processing'
#paperurl: 'https://doi.org/10.1364/OE.444864'
#citation: 'Nelson Diaz, Alejandro Alvarado, Pablo Meza, Felipe Guzmán, and Esteban Vera, &quot;Multispectral Filter Array Design by Optimal Sphere Packing.&quot; <i>IEEE. ransactions on Image Processing,</i>. vol. 32, pp. 3634-3649, 2023.'
---

Recommended citation: E. Vera, F. Guzmán and **N. Diaz**, "Shuffled Rolling Shutter Camera," <i> Springer International Publishing,</i> vol. 32, pp. 499-513, 2023. [[DOI]](https://doi.org/10.1007/978-3-031-39062-3_27).

Multispectral Imaging (MSI) collects a datacube of spatio-spectral information of a scene. Many acquisition methods for spectral imaging use scanning, preventing its widespread usage for dynamic scenes. On the other hand, the conventional color filter array (CFA) method often used to sample color images has also been extended to snapshot MSI using a Multispectral Filter Array (MSFA), which is a mosaic of selective spectral filters placed over the Focal Plane Array (FPA). However, even state-of-the-art MSFAs coding patterns produce artifacts and distortions in the reconstructed spectral images, which might be due to the non-optimal distribution of the spectral filters. To reduce the appearance of artifacts and provide tools for the optimal design of MSFAs, this paper proposes a novel mathematical framework to design MSFAs using a Sphere Packing (SP) approach. By assuming that each sampled filter can be represented by a sphere within the discrete datacube, SP organizes the position of the equal-size and disjoint spheres’s centers in a cubic container. Our method is denoted Multispectral Filter Array by Optimal Sphere Packing (MSFA-OSP), which seeks filter positions that maximize the minimum distance between the spheres’s centers. Simulation results show an image quality improvement of up to 2 dB and a remarkable boost in spectral similarity when using our proposed MSFA design approach for a variety of reconstruction algorithms. Moreover, MSFA-OSP notably reduces the appearance of false colors and zipper effect artifacts, often seen when using state-of-the-art demosaicking algorithms. Experiments using synthetic and real data prove that the proposed MSFA-OSP outperforms state-of-the-art MSFAs in terms of spatial and spectral fidelity.


### Cite

```
@Inbook{Vera2024,
author="Vera, Esteban
and Guzman, Felipe
and Diaz, Nelson",
editor="Liang, Jinyang",
title="Shuffled Rolling Shutter Camera",
bookTitle="Coded Optical Imaging",
year="2024",
publisher="Springer International Publishing",
address="Cham",
pages="499--513",
abstract="This chapter provides a comprehensive and up-to-date review of the rolling shutter (RS) mechanism found in complementary metal-oxide semiconductor (CMOS) imaging sensors as a coding opportunity for high-speed videos. Based on this, we present a cutting-edge readout architecture called shuffled rolling shutter (SRS) that optimally designs the scanlines entries of the RS for improved sampling of the space-time datacube. The RS restriction implies that only one entry per column is sampled at each exposure time. This restriction can be modeled using a three-dimensional N2 queens problem (3DN2QP), such that the optimal design of entries is computed straightforwardly, solving a sphere packing (SP) problem. The main advantage of packing equal-size spheres in a cubic container is promoting uniform spatiotemporal sampling. Simulation and experimental results prove that with the captured measurements using the proposed SRS, we can recover the underlying video from a snapshot. This opens the avenue for the development of new CMOS imaging detectors with shuffled positions of the RS, now able to turn a typical nuisance into an opportunity to capture and recover videos from snapshots.",
isbn="978-3-031-39062-3",
doi="10.1007/978-3-031-39062-3_27",
url="https://doi.org/10.1007/978-3-031-39062-3_27"
}
```
<a href="https://www.scimagojr.com/journalsearch.php?q=25534&amp;tip=sid&amp;exact=no" title="SCImago Journal &amp; Country Rank"><img border="0" src="https://www.scimagojr.com/journal_img.php?id=25534" alt="SCImago Journal &amp; Country Rank"  /></a>
