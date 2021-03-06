---
layout: page
title: ECEncrypt
description: Image Encryption Technique
img: /assets/img/encrypt.png
---

This project implements an image encryption scheme operating in the spatial domain with confusion and diffusion being its foundational concepts. Encryption is done via a three-step process, namely, *shuffling & swapping*, *mutation* and finally a *XOR operation*. 

A user entered key directly participates in the generation of a pseudo random number array. This array then serves as an encryption tool for the 3 constituent phases. 
- The first phase of shuffling and swapping introduces visual degradation thereby making the image unrecognizable as it directly targets the breakage of horizontal as well as vertical correlations. 
- This operation is followed by mutation which incorporates inversion of one randomly chosen bit in each pixel. 
- Finally, the random number array is applied again to perform a basic XOR operation on the whole image. 

Performance of proposed approach has been evaluated both quantitatively and qualitatively using standard metrics such as correlation, entropy, NPCR, UACI. In addition, results of key sensitivity test, cut test and dispersion test instantiate the strength of proposed scheme.
<br>
This work was done as a part of internship at SAG,DRDO.
<br>
<br>
<a href="{{ site.baseurl }}{% link /assets/pdf/ImageEncryption.pdf %}" class="button"><i class="far fa-file-powerpoint fa-1g"></i> Poster</a>
