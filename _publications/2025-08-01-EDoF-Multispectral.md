---
title: "Multispectral Extended Depth-of-Field Imaging via Stochastic Wavefront Optimization"
collection: publications
permalink: /publication/2025-08-01-Multispectral-Extended-Depth-of-Field-Imaging-via-Stochastic-Wavefront-Optimization
excerpt: 
date: 2025-08-01
venue: 'IEEE Open Journal on Signal Processing'
#paperurl: '[https://doi.org/10.1364/OE.561323](https://doi.org/10.1364/OE.561323)'
#citation: 'Exequiel Oliva, Nelson Diaz, Samuel Pinilla, and Esteban Vera, &quot;Multispectral Extended Depth-of-Field Imaging via Stochastic Wavefront Optimization.&quot; <i>IEEE Open Journal on Signal Processing,</i>. vol. 6, pp. 965 - 974, 2025.'
---


Recommended citation: E. Oliva, **N. Diaz**, S. Pinilla, and E. Vera, "Multispectral Extended Depth-of-Field Imaging via Stochastic Wavefront Optimization," <i> IEEE Open Journal on Signal Processing,</i> vol. 6, pp. 965 - 974, 2025. [[DOI]](https://ieeexplore.ieee.org/abstract/document/11106763), [[Code]](https://github.com/nelson10/MSFA-DOE.git), [[COSI_2025_poster]](https://nelson10.github.io/files/Poster5.pdf).

Extended depth-of-field (EDoF) is a desirable attribute for imaging systems where all features in the scene are in focus despite their relative distance. Traditional imaging systems can achieve EDoF by reducing the aperture size at the expense of signal-to-noise ratio, particularly relevant in spectral imaging systems where incoming light is further divided. By designing and integrating diffractive optical elements (DOEs) placed at the aperture plane of the imaging system, wavefront coding has enabled EDoF while maintaining a larger aperture size at the expense of post-processing. Nevertheless, chromatic aberrations may appear and can often be confused by defocus, jeopardizing the fidelity of the reconstructions. This work presents a novel design approach for a multispectral-aware DOE for EDoF. By considering and modeling a refractive-diffractive optical setup, our proposed system uses the stochastic optimization framework to optimize DOE patterns to preserve spectral fidelity while extending the depth-of-field simultaneously. The optimization process exploits the covariance matrix adaptation evolution strategy (CMA-ES), efficiently exploring complex, high-dimensional phase configurations without the need for explicit gradient information. The optimized DOE is constantly evaluated in a simulated imaging pipeline where the EDoF multispectral datacube is deblurred using Richardson-Lucy deconvolution. Both qualitative and quantitative results demonstrate that the proposed DOE significantly improves depth invariance and spectral fidelity of the reconstructed datacubes compared to conventional and state-of-the-art DOE designs, making it a cost-effective solution for real-world multispectral EDoF applications.

### Cite

```
@ARTICLE{11106763,
  author={Oliva, Exequiel and Díaz, Nelson and Pinilla, Samuel and Vera, Esteban},
  journal={IEEE Open Journal of Signal Processing}, 
  title={Multispectral Extended Depth-of-Field Imaging via Stochastic Wavefront Optimization}, 
  year={2025},
  volume={6},
  number={},
  pages={965-974},
  keywords={Optimization;Imaging;Optical imaging;Optical diffraction;Optical sensors;Optical refraction;Optical filters;Apertures;Signal processing algorithms;Polynomials;Diffractive optical element;extended depth-of-field;multispectral imaging;stochastic optimization;wavefront coding},
  doi={10.1109/OJSP.2025.3595046}}
```
<a href="https://www.scimagojr.com/journalsearch.php?q=21101081712&amp;tip=sid&amp;exact=no" title="SCImago Journal &amp; Country Rank"><img border="0" src="https://www.scimagojr.com/journal_img.php?id=21101081712" alt="SCImago Journal &amp; Country Rank"  /></a>
