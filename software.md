---
title: Software
feature_text: |
  ## <span style="color:black">Software</span>
feature_image: "../assets/images/tibet/tibet_s1_a41_210504-210516_1.jpg"
---

Below is publicly available software developed by us.


###### alos2App
alos2App is an application that can process multi-mode SAR data acquired by the JAXA ALOS-2 satellite. The application is now part of the [ISCE](https://github.com/isce-framework/isce2) software. Future plans include the support for the upcoming ALOS-4 satellite. Major algorithms are discribed in [Liang and Fielding, 2017a, _IEEE TGRS_](https://ieeexplore.ieee.org/document/7852444) and [Liang and Fielding, 2017b, _IEEE TGRS_](https://ieeexplore.ieee.org/document/7857102). Here is an example of ScanSAR-stripmap interfeorgram processed by alos2App and featured in the journal [_Science_](https://science.sciencemag.org/content/371/6532/876/tab-pdf).


###### alos2burstApp
alos2burstApp is an application for processing ALOS-2 ScanSAR data in a burst-by-burst fashion. The application is now part of the [ISCE](https://github.com/isce-framework/isce2) software. The implemented algorithms can be found in [Liang and Fielding, 2017, _IEEE TGRS_](https://ieeexplore.ieee.org/document/7852444).


###### alosStack
alosStack is an application for processing an ALOS-2 InSAR stack. The application is part of the [ISCE](https://github.com/isce-framework/isce2) software. Future plans also include the support for the upcoming ALOS-4 satellite. It also makes use of the algorithms developed in [Liang and Fielding, 2017a, _IEEE TGRS_](https://ieeexplore.ieee.org/document/7852444) and [Liang and Fielding, 2017b, _IEEE TGRS_](https://ieeexplore.ieee.org/document/7857102). The output of the application is supported by [MintPy](https://github.com/insarlab/MintPy).

{% include figure.html image="../assets/images/software/ALOS2_ISCE2.jpg" caption="alos2App, alos2burstApp and alosStack, and their sample processing results." position="center" width="2000" %}


###### Sentinel-1 TOPS mode ionospheric correction software
The software performs ionospheric correction for the C-band Sentinel-1 TOPS mode InSAR data. The software is now part of the topsApp in [ISCE](https://github.com/isce-framework/isce2) software. We will soon get it into topsStack for the ionospheric correction of TOPS stack. The detailed algorithms implemented are discribed in [Liang et al., 2019, _IEEE TGRS_](https://ieeexplore.ieee.org/document/8706258). While ionospheric effects at C-band were mostly not considered as a big issue or even misinterpreted as orbit fringes before, recent studies demonstrated that they can be very significant in some cases ([Liang et al., 2019, _IEEE TGRS_](https://ieeexplore.ieee.org/document/8706258)).

{% include figure.html image="../assets/images/software/all_chile_a149.jpg" caption="Ionospheric correction of a stack of Sentinel-1 TOPS interferograms in northern Chile (Track A149)" position="center" width="1200" %}

 