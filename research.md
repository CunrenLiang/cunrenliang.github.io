---
title: Research
feature_text: |
  ## <span style="color:black">Research</span>
feature_image: "../assets/images/tibet/tibet_s1_a41_210504-210516_8.jpg"
---

Synthetic aperture radar (SAR) uses microwaves to image the Earth and other planetary bodies. Unlike most optical instruments, SAR is an active sensor that transmits pulses toward the surface and then receives the backscattered echoes. Therefore, SAR does not require solar illumination and can acquire images day or night. Moreover, microwaves can penetrate clouds, enabling SAR to operate under all weather conditions. A significant advantage of remote sensing with SAR is that the entire process, from the underlying physical principles to data processing techniques, is highly quantitative, enabling the retrieval of physical parameters with high precision.

{% include figure.html image="../assets/images/research/sentinel1-magellan.jpg" caption="Left: Earth observation through clouds with synthetic aperture radar (Credit: ESA). Right: Magellan radar mission to Venus, launched aboard space shuttle Atlantis (Credit: NASA)." position="center" width="1000" %}

The development of synthetic aperture radar interferometry (InSAR) over the last few decades has further enabled SAR to measure the Earth's surface in the third dimension, providing information on topography and surface deformation. InSAR measures surface deformation using the phase of radar waves, whose wavelengths range from a few to several tens of centimeters, and thus can achieve the amazing centimeter- to millimeter-level precision. Coincidentally, many deformations on the Earth’s surface are comparable in magnitude to radar wavelengths (yes, surface deformation occurs almost everywhere on Earth. You just cannot see it in most cases, but InSAR can). Therefore, InSAR is widely used in engineering and scientific applications and has even revolutionized research in related fields. Driven by their unique capabilities and a growing range of applications, SAR and InSAR are expanding beyond academia, with an increasing number of companies around the world commercializing these technologies. Analysts estimated the global SAR market at roughly $4 billion in 2021 and projected it to nearly double over the following five years ([Rosen, 2021, _Science_](https://science.sciencemag.org/content/371/6532/876)).


###### Radar Signal and Image Processing
Radar signal and image processing draws on theories from statistics, signal processing, electromagnetic scattering, and geodesy. A typical example is SAR focusing. The original data acquired by SAR are called raw data, which look much like pure noise if displayed as an image. Through signal processing techniques, or focusing, an image can be formed. Further processing, such as denoising, is thus performed in the image domain for numerous applications. One of our group’s research focuses is on the processing of data acquired in advanced modes, such as spotlight, ScanSAR, TOPS and SweepSAR, which requires more sophisticated signal processing algorithms (e.g. [Liang et al., 2017, _IEEE TGRS_](https://ieeexplore.ieee.org/document/8038865)).

{% include figure.html image="../assets/images/research/pta+sar_image.jpg" caption="Left: radar signal focusing exemplified by point target analysis. Right: a focused high resolution X-band satellite SAR image (Credit: Capella Space)." position="center" width="1000" %}


###### Synthetic Aperture Radar Interferometry (InSAR)

{% include figure.html image="../assets/images/research/insar.jpg" caption="Synthetic Aperture Radar INterferometry (InSAR)" position="right" width="700" %}

A SAR image is a complex image with both magnitude and phase. By comparing the phases of two radar images, InSAR can measure topography or deformation on the Earth’s surface. The cool thing about satellite InSAR is that it measures deformation on the ground with centimeter or even millimeter precision at an altitude of about 800 km above the Earth's surface. Furthermore, the measurement is an image, which is like deploying millions of Global Navigation Satellite System (GNSS) stations on the ground to monitor surface deformations. By processing many InSAR images with time series analysis techniques, we can further track the temporal evolution of surface deformation, which has numerous applications.


InSAR involves a number of processing steps and still has challenges or even bottlenecks. The algorithms are continuously evolving. With an ever-growing number of satellite SAR missions and advanced imaging capabilities, the amount of SAR data is exploding - SAR is also entering the big data era. This brings new challenges and opportunities, especially for InSAR time series analysis, and requires efficient processing techniques.


Our group primarily works on the theory and technical development of InSAR (e.g. [Liang and Fielding, 2017a, _IEEE TGRS_](https://ieeexplore.ieee.org/document/7852444), [Liang and Fielding, 2017b, _IEEE TGRS_](https://ieeexplore.ieee.org/document/7857102)), with a particular focus on L-band as we enter the golden age of L-band satellite SAR missions. We seek to understand the physical processes, signals, and errors that shape InSAR measurements through mathematical modeling and to translate this understanding into improved InSAR techniques for geodetic and geophysical applications. In the long run, one of our goals is to enable the measurement of global tectonic motions solely through InSAR, without relying on external constraints such as GNSS.


###### InSAR Error Corrections

While the microwave is travelling in the atmosphere, its phase is mostly affected by two layers of the atmosphere including troposphere and ionosphere. The troposphere is the lowest layer of Earth’s atmosphere. The water vapor in troposphere causes phase delay to microwave signals. The ionosphere can extend from 50 km to 1000 km above the Earth’s surface. Its formation is mainly because the neutral atoms or molecules in the atmosphere eject free electrons after absorbing solar radiation. The free electrons cause a phase shift to the traversing microwave signal. Previously our group has extensively studied the effects of ionosphere and developed a number of techniques to correct its effects.

{% include figure.html image="../assets/images/research/ionosphere+correction.jpg" caption="Left: Ionosphere and satellite synthetic aperture radar. Right: InSAR ionosphere correction result (copyright: Liang Group)." position="center" width="1100" %}

The measured deformation by InSAR contains not only deformation of interest, but also other physical components including the currently known ocean tide and solid earth tide. They mostly introduce very long wavelength signals in the measurement and did not raise wide concern before. However, they are becoming increasingly important as InSAR is moving forward from small-scale deformation measurement to large-scale or even continental-scale measurement thanks to the advanced imaging capabilities of present and future SAR missions.

InSAR processing also introduces errors in the final results. Our group works on the correction of all sources of errors to improve the accuracy and precision of InSAR measurements (e.g. [Liang and Fielding, 2017, _IEEE TGRS_](https://ieeexplore.ieee.org/document/7852444), [Liang et al., 2019, _IEEE TGRS_](https://ieeexplore.ieee.org/document/8706258)).


###### InSAR Applications in Geophysics and other Fields
The unique capabilities of InSAR make it widely used in science and engineering. Researchers have been using InSAR to study earthquakes, tectonics, glaciers, volcanoes, landslide, hydrology etc. InSAR is also used in a number of fields in engineering such as the monitoring of critical infrastructures (e.g. buildings, bridges, dams, tunnels, subways and railways), city subsidence, land subsidence due to oil and water pumping, mining etc. New applications are also emerging in other fields. In some fields, it would have been difficult or even impossible to accomplish without the help of InSAR. Previously our group had collaborated with researchers at major universities such as UC Berkeley, UCLA and Caltech to apply InSAR to the study of significant problems in geophysics (e.g. [Hamling et al., 2017, _Science_](https://science.sciencemag.org/content/356/6334/eaam7194)).

{% include figure.html image="../assets/images/research/Kaikoura_earthquake.jpg" caption="InSAR data used to study the 2016 Mw 7.8 Kaikōura earthquake in New Zealand. Left: ALOS-2 interferogram. Right: Best-fitting crustal fault model." position="center" width="1000" %}


###### Natural Hazard Response with SAR

Radar can image in all weather conditions and without the need of illumination from the Sun. This makes it particularly useful in areas like the cloudy or rainy southern China where geohazards can easily happen. As the number of civil and commercial SAR satellites is growing rapidly, we may be able to detect daily or even hourly surface changes. The results have already been proved to be of great values to government agencies. Previously we have worked with researchers to produce damage proxy maps (DPM) that map the damages caused by various natural disasters. Many of the results have been used to aid in the response of these disasters (e.g. [Yun et al., 2015, _SRL_](https://pubs.geoscienceworld.org/ssa/srl/article/86/6/1549/315478/Rapid-Damage-Mapping-for-the-2015-Mw-7-8-Gorkha)).

{% include figure.html image="../assets/images/research/dpm_nepal_earthquake.jpg" caption="Damage proxy map of the 2015 Nepal earthquake generated using SAR data." position="center" width="800" %}


###### Current Projects
* 国家高层次人才计划项目（青年）, PI
* 复杂困难地区大范围L波段InSAR时序分析技术研究, PI, National Natural Science Fundation of China
* [Calibration/Validation and Science Team (CVST) of ALOS-4 mission](https://www.eorc.jaxa.jp/ALOS/en/alos-4/a4_calval_e.htm), PI, Japan Aerospace Exploration Agency (JAXA), Japan
* New Techniques for Monitoring Carbon Stock and Flux in Southeast Asia using Spaceborne SAR and LiDAR Observations, Co-PI, Space Technology Development Programme, Singapore
* Integrating Volcano and Earthquake Science and Technology (InVEST) in Southeast Asia, Co-PI, Ministry of Education, Singapore
