# EO-PERSIST_InSAR_Ionosphere_Tutorial

**Introduction**
---
This notebook provides a step-by-step guide for processing ALOS2 PALSAR2 stripmap images to generate interferograms corrected for ionospheric effects. It uses ISCE2’s alosStack processor (Liang et al., 2019) to process all images as a stack (with one reference image in the stack) and calculates and corrects the ionospheric effects across the image stack network. It offers clarity about the specific steps involved, helping users better understand the processes taking place. 


**Aknownledgements**
---

This notebook was created under the framework of EO-PERSIST project funded by EU and the HORIZON TMA MSCA Staff Exchanges call. The ALOS2 PALSAR2 data used for the demostration purposes are made available through the ESA JAXA Mutual SAR Cooperation Agreement. The data was provided from FMI to NTUA (Pelagia Koutsantoni) for the research and educational purposes. The InSAR processing is implemented with ISCE2 (Interferometric synthetic aperture radar Scientific Computing Environment 2) software, a open source software under the terms of the the Apache License, initially funded by NASA's Earth Science Technology Office (ESTO) under the Advanced Information Systems Technology (AIST) 2008 and currently funded under the NASA-ISRO SAR (NISAR) project.

