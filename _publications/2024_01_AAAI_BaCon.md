---
title: "[AAAI2024] BaCon: Boosting Imbalanced Semi-supervised Learning via Balanced Feature-Level Contrastive Learning"
collection: publications
permalink: /publication/2024_01_AAAI_BaCon
excerpt: 'Qianhan Feng, Lujing Xie, Shijie Fang, Tong Lin*'
date: 2024-02-25
venue: 'Proceedings of AAAI'
---
**Qianhan Feng**, Lujing Xie, Shijie Fang, Tong Lin*

Semi-supervised Learning (SSL) reduces the need for extensive annotations in deep learning, but the more realistic challenge of imbalanced data distribution in SSL remains largely unexplored. In Class Imbalanced Semi-supervised Learning (CISSL), the bias introduced by unreliable pseudolabels can be exacerbated by imbalanced data distributions. Most existing methods address this issue at instance-level through reweighting or resampling, but the performance is heavily limited by their reliance on biased backbone representation. Some other methods do perform feature-level adjustments like feature blending but might introduce unfavorable noise. In this paper, we discuss the bonus of a more balanced feature distribution for the CISSL problem, and further propose a Balanced Feature-Level Contrastive Learning method (BaCon). Our method directly regularizes the distribution of instances’ representations in a well-designed contrastive manner. Specifically, class-wise feature centers are computed as the positive anchors, while negative anchors are selected by a straightforward yet effective mechanism. A distribution-related temperature adjustment is leveraged to control the class-wise contrastive degrees dynamically. Our method demonstrates its effectiveness through comprehensive experiments on the CIFAR10-LT, CIFAR100-LT, STL10-LT, and SVHN-LT datasets across various settings. For example, BaCon surpasses instance-level method FixMatch-based ABC on CIFAR10-LT with a 1.21% accuracy improvement, and outperforms state-of-the-art featurelevel method CoSSL on CIFAR100-LT with a 0.63% accuracy improvement. When encountering more extreme imbalance degree, BaCon also shows better robustness than other methods.  
[[Accessible PDF]](https://fqhank.github.io/fengqianhan.github.io/files/AAAI24-Feng.pdf)  

Recommended citation:   
@inproceedings{feng2024bacon,  
  title={Deep homography for efficient stereo image compression},  
  author={Deng, Xin and Yang, Wenzhe and Yang, Ren and Xu, Mai and Liu, Enpeng and Feng, Qianhan and Timofte, Radu},  
  booktitle={Thirty-Seventh {AAAI} Conference on Artificial Intelligence, {AAAI} 2024},  
  year={2024}  
}
