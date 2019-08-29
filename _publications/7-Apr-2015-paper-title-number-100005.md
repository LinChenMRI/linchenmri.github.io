---
title: "Super-resolved enhancing and edge deghosting (SEED) for spatiotemporally encoded single-shot MRI"
collection: publications
permalink: /publications/7-Apr-2015-paper-title-number-100005
excerpt: '<b>Super-resolved enhancing and edge deghosting (SEED) is the state-of-the-art super-resolved method for spatiotemporally encoded (SPEN) single-shot MRI</b><br><center><img width = "100%" src="http://linchenmri.github.io/files/2015-MIA-SEED.png" alt=""></center>'
date: 7-Apr-2015
venue: 'Medical Image Analysis'
citation: '<b>Chen L</b>, Li J, Zhang M, Cai S, Zhang T, Cai C, Chen Z. Super-resolved enhancing and edge deghosting (SEED) for spatiotemporally encoded single-shot MRI. Med Image Anal 2015;23(1):1-14.'
---

Spatiotemporally encoded (SPEN) single-shot MRI is an ultrafast MRI technique proposed recently, which utilizes quadratic rather than linear phase profile to extract the spatial information. Compared to the echo planar imaging (EPI), this technique has great advantages in resisting field inhomogeneity and chemical shift effects. Super-resolved (SR) reconstruction is adopted to compensate the inherent low resolution of SPEN images. Due to insufficient sampling rate, the SR image is challenged by aliasing artifacts and edge ghosts. The existing SR algorithms always compromise in spatial resolution to suppress these undesirable artifacts. In this paper, we proposed a novel SR algorithm termed super-resolved enhancing and edge deghosting (SEED). Different from artifacts suppression methods, our algorithm aims at exploiting the relationship between aliasing artifacts and real signal. Based on this relationship, the aliasing artifacts can be eliminated without spatial resolution loss. According to the trait of edge ghosts, finite differences and high-pass filter are employed to extract the prior knowledge of edge ghosts. By combining the prior knowledge with compressed sensing, our algorithm can efficiently reduce the edge ghosts. The robustness of SEED is demonstrated by experiments under various situations. The results indicate that the SEED can provide better spatial resolution compared to state-of-the-art SR reconstruction algorithms in SPEN MRI. Theoretical analysis and experimental results also show that the SR images reconstructed by SEED have better spatial resolution than the images obtained with conventional k-space encoding methods under similar experimental condition.

<center><img width = "100%" src="http://linchenmri.github.io/files/2015-MIA-SEED.png" alt=""></center>


<br>
<a href='https://doi.org/10.1016/j.media.2015.03.004'>Download paper here</a>

<br>
<a href='https://github.com/LinChenMRI/SEED-for-SPEN-MRI'>Download code here</a>