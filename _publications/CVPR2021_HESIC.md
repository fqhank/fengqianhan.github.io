---
title: "Deep Homography for Efficient Stereo Image Compression"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Xin Deng, Wenzhe Yang, Ren Yang, Mai Xu*, Enpeng Liu, Qianhan Feng, Radu Timofte'
date: 2021-06-21
venue: 'Proceedings of CVPR'
---
[[Accessible PDF]](https://fqhank.github.io/fengqianhan.github.io/files/Deng_Deep_Homography_for_Efficient_Stereo_Image_Compression_CVPR_2021_paper.pdf)  
Xin Deng, Wenzhe Yang, Ren Yang, Mai Xu*, Enpeng Liu, **Qianhan Feng**, Radu Timofte

In this paper, we propose HESIC, an end-to-end trainable deep network for stereo image compression (SIC). To fully explore the mutual information across two stereo images,
we use a deep regression model to estimate the homography matrix, i.e., H matrix. Then, the left image is spatially transformed by the H matrix, and only the residual information
between the left and right images is encoded to save bitrates. A two-branch auto-encoder architecture is adopted in HESIC, corresponding to the left and right images, respectively. For entropy coding, we use two conditional stereo entropy models, i.e., Gaussian mixture model (GMM) based and context based entropy models, to fully explore the correlation between the two images to reduce the coding bit-rates. In decoding, a cross quality enhancement module is proposed to enhance the image quality based on inverse H matrix. Experimental results show that our HESIC outperforms stateof-the-art SIC methods on InStereo2K and KITTI datasets both quantitatively and qualitatively. Code is available at https://github.com/ywz978020607/HESIC.

Recommended citation in BibTeX format:  
@inproceedings{deng2021deep,  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; title={Deep homography for efficient stereo image compression},  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; author={Deng, Xin and Yang, Wenzhe and Yang, Ren and Xu, Mai and Liu, Enpeng and Feng, Qianhan and Timofte, Radu},  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; pages={1492--1501},  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;year={2021}  
}.
