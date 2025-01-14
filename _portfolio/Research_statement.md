---
title: "Research Statement"
excerpt: "Research Thrusts"
collection: portfolio
---

<div style="text-align: justify">  I am interested in developing a computational imaging system that improve our understanding of the world. 
In this regard, my research has focused on 3 different subareas. First, \textbf{applied sphere packing for 
single-snapshot spectral imaging/video sensing}, where I have designed and built a \textit{multispectral 
filter array with an optimal sensing distribution} that overcomes the limitations of traditional multispectral filters 
(color distortion, zipper effect, and color artifacts). Moreover, I have developed a novel **shuffled rolling shutter 
camera** that eliminate the nuisance artifacts of the rolling shutter mechanism found in complementary
metal oxide semiconductor (CMOS) detectors. Second, **computational imaging and applied optics** 
where I explore different topics such adaptive compressive spectral imaging sensing to improve the quality 
of spectral image reconstruction, wavefront coding using diffractive optical elements for solving tasks
such as extended-depth-of-field (EDoF), coded aperture design for phase retrieval. Finally, **remote sensing**,
where I have also developed *adaptive compressive multispectral imaging and video acquisition systems* to improve
the image quality and perform specific tasks, such as, classification. I also *developed and implemented
an algorithm for ground filtering using point cloud processing captured using Light Detection and Ranging* (LiDAR). </div>

<div style="text-align: justify"> This research thrusts will have a broad impact on several domains including consumer photography, surveillance, 
remote sensing, target identification, medical applications, and computational imaging, and applied optics. </div>

\section*{Research Thrusts}

My research involves different interconnected areas of electronic engineering, such as signal processing, digital image processing, and compressive sensing. It also requires knowledge of computer science, such as algorithm design, linear algebra, numerical analysis, mathematical modeling, software expertise, and publication skills to address multidimensional data. These competencies were learned during my bachelor's, master's, and doctoral studies. 

Specifically, I can group my research topics in three subareas:

 * **Applied sphere packing for single-snapshot sensing**: I exploits the properties of regular and irregular sphere packing to design novel sensing approaches for snapshot spectral imaging and snapshot video.  My recent publication is Journal [J2] and conference [C1], where we designed a novel snapshot video sampling scheme using sphere packing and shuffling rolling shutter scanlines of the CMOS camera. The abilities with deep learning, ultrasound imaging, and temporal spectral video are shown in references [C2], [C3], and [C4], respectively. One of my most outstanding publication is [J1] published in The IEEE Transactions on image processing a journal with impact factor 10.8, where I introduced sphere packing for multispectral imaging demosaicking, which yield a general framework for spectral imaging acquisition achieving notable image quality, independent of the reconstruction approach (classical interpolation, convex optimization, novel neural networks).

*  **Computational imaging and applied optics**: Adaptive compressive spectral imaging sensing, wavefront coding for extended-depth-of-field, and coded aperture design for phase retrieval (summited). In detail, journals [J1-J2, J4-J5] show compressive spectral imaging and adaptive sensing expertise. Journal [J5] extends my master work in high dynamic range compressive spectral imaging (CSI) using real data and using an optimal coded aperture according to restricted isometry property (RIP), such as blue noise patterns. 

* **Remote sensing**: Two modalities are highlighted here, compressive spectral imaging classification, and point cloud processing captured using Light Detection and Ranging (LiDAR). My work published in [J4] combines a two-arm optical system, the CSI architecture includes one arm that samples the projection of multispectral data and the other arm that captures hyperspectral projections, and an adaptive system is used to design the complementary coded aperture patterns to improve the spectral classification accuracy. The journal in [J3] shows my expertise in other types of multidimensional data, such as point clouds acquired using LiDAR for a specific task such as ground filtering.


%Specifically, [J5, C5] introduced an adaptive system for colored coded aperture snapshot spectral imager (C-CASSI) to improve the image reconstruction quality. 

1. [J1] **N. Diaz**, A. Alvarado, P. Meza, F. Guzmán and E. Vera, Multispectral Filter Array Design by Optimal Sphere Packing," in IEEE Transactions on Image Processing, vol. 32, pp. 3634-3649, 2023, \href{https://doi.org/10.1109/TIP.2023.3288414}{doi:10.1109/TIP.2023.3288414}.
2. [J2] E. Vera, F. Guzman, **N. Díaz**, Shuffled Rolling Shutter for Snapshot Temporal Imaging, Opt. Express, 2022, \href{https://doi.org/10.1364/OE.444864}{doi.org/10.1364/OE.444864}.
3. [J3] **N. Díaz**, et al, Real-time ground filtering algorithm of cloud points acquired using Terrestrial Laser Scanner”, International JAG, 2021, \href{https://doi.org/10.1016/j.jag.2021.102629}{doi.org/10.1016/j.jag.2021.102629}.
4. [J4] **N. Díaz**, Juan Ramirez, Esteban Vera, Henry Arguello. Adaptive multisensor acquisition via spatial contextual information for compressive spectral image classification, IEEE JSTARS, 2021, \href{https://doi.org/10.1109/JSTARS.2021.3111508}{10.1109/JSTARS.2021.3111508}.
5. [J5] **N. Díaz**, Carlos Hinojosa, Henry Arguello, Adaptive grayscale compressive spectral imaging using optimal blue noise coding patterns, Optics \& Laser Technology, 2019, \href{https://doi.org/10.1016/j.optlastec.2019.03.038}{doi.org/10.1016/j.optlastec.2019.03.038}.
6. [J6] **N. Díaz**, H. Rueda, H. Arguello, Adaptive filter design via a gradient thresholding algorithm for compressive spectral imaging, App. Optics, 2018, https://doi.org/10.1364/AO.57.004890.

* [C1] F. Guzman, **N. Díaz** E. Vera, Improved Compressive Temporal Imaging using a Shuffled Rolling Shutter, OSA Optical Sensors and Sensing Congress, virtual, 2021.
*  [C2] J. Bacca, **N. Díaz**, H. Arguello, Compressive classification via deep learning using single-pixel measurement, 2020 Data Compression Conference, USA, 2020.
* [C3] **N. Díaz**, A. Basarab, J-Y Tourneret, H. Arguello, \textbf{Cardiac motion estimation} using convolutional sparse coding, 2019 27th (EUSIPCO), España, 2019.
*  [C4] **N. Díaz**, A. Basarab, J-Y Tourneret, H. Arguello, Adaptive coded aperture design by motion estimation using convolutional sparse coding in compressive spectral video sensing, CAMSAP, France, 2019.
* [C5] **N. Díaz**, J. Bacca, H. Arguello, Gradient thresholding algorithm for adaptive colored coded aperture design in compressive spectral imaging, OSA Optical Sensors and Sensing Congress, USA, 2017.

**Future Research Plans**

I will be working in two areas:

1. <div style="text-align: justify">  **Optimal coded apertures design and wavefront coding for single-snapshot sensing:** The acquisition of signals in high-dimensions involves the design of sampling schemes that promote total uniform sampling (uniform packing) and on average uniform sampling (irregular packing). This area has profound applications in video, imaging, depth and light field sensing. The big challenge in this area is design the sensing pattern such that promotes the invertibility of inverse problem. Futhermore, sphere packing optimal density is only determine in 2, 3, 8 and 24 dimensions. Wavefront coding design is used to solve specific tasks such extended-depth-of-field. </div> 
   
3. <div style="text-align: justify"> **Deep learning applied to computational imaging:** Novel algorithms that exploit enormous amounts of data have revolutionized the reconstruction in all the areas of applied optics and computational imaging. Currently, it is crucial to design both the optics and the reconstruction leveraging novel techniques such as deep image prior, and design end-to-end, where both the optical encoding element is designed jointly with the reconstruction algorithm. Furthermore, a big challenge in neural networks is the explainability because they are assumed as black-box approach. To address this challenge novel methods relying on unfolding promotes explainability by converting the layers of the network in iterations of an optimization problem.</div>

    

**Research and collaborations**:

I also believe that interdisciplinary research is a crucial element and may provide exciting and important challenges. In this regard, I have been fortunate enough to have worked with scientists from several disciplines. I have worked with Prof. **Henry Arguello Fuentes**, Prof. **Hoover Rueda** and Prof. **Jorge Bacca** (Universidad Industrial de Santander, Department of Computer Science, Bucaramanga, Colombia) in projects concerning high dynamic range in compressive spectral imaging, adaptive compressive spectral imaging and video, and adaptive multisensor spectral image classification. During my postdoctoral stage, I have the opportunity to work on shuffled rolling shutter camera with Dr. **Esteban Vera Rojas** (Pontificia Universidad Católica de Valparaíso) who is one of the leading researchers in computational imaging. Recently, I spent six weeks visiting Prof. **Pablo Meza** (Universidad de la Frontera, School of Electrical Engineering, Temuco, Chile). During this time, I learned about test-bed experiments for multispectral imaging and have come away with several applications in spectral video and sphere packing. Recently, I also worked with the computational ultrafast photography involving researchers such as Dr. **Jinyang Liang** Canada Research Chair in ultrafast computational imaging, and Miguel Marquez postdoctoral fellow at the Institut National de la Recherche Scientifique, Montreal, Canada. In ultrafast photography I proposed a novel sensing scheme involving sphere packing and implicit neural representation as reconstruction approach. Currently, I am working on a project with **Karen Erguiazarian**, who is a Professor of Signal Processing at the Department of Computing Sciences, Tampere University, Tampere, Finland. And **Samuel Pinilla**, who is researcher at Rutherford Appleton Laboratory, Science and Technology Facilities Council, UK. The project is about a lensless camera to improve spectral classification using Hardware-in-the-loop methodology. I continue to maintain active collaborations with all these researchers. I have realized that research collaboration promotes novelty and innovation with these and other researchers and scientists.
