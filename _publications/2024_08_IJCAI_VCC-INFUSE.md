---
title: "[IJCAI2024] VCC-INFUSE: Towards Accurate and Efficient Selection of Unlabeled Examples in Semi-supervised Learning"
collection: publications
permalink: /publication/2024_08_IJCAI_VCC-INFUSE
excerpt: 'Shijie Fang, Qianhan Feng, Tong Lin*'
date: 2024-08-03
venue: 'Proceedings of IJCAI'
--- 
Shijie Fang†, **Qianhan Feng†**, Tong Lin*
† Equal contribution. Equal first author of this paper.

Despite the progress of Semi-supervised Learning (SSL), existing methods fail to utilize unlabeled data effectively and efficiently. Many pseudo-label-based methods select unlabeled examples based on inaccurate confidence scores from the classifier. Most prior work also uses all available unlabeled data without pruning, making it difficult to handle large amounts of unlabeled data. To address these issues, we propose two methods: Variational Confidence Calibration (VCC) and Influence-Function-based Unlabeled Sample Elimination (INFUSE). VCC is an universal plugin for SSL confidence calibration, using a variational autoencoder to select more accurate pseudo labels based on three types of consistency scores. INFUSE is a data pruning method that constructs a core dataset of unlabeled examples under SSL. Our methods are effective in multiple datasets and settings, reducing classification errors rates and saving training time. Together, VCC-INFUSE reduces the error rate of FlexMatch on the CIFAR-100 dataset by 1.08% while saving nearly half of the training time.
[[Accessible PDF]](https://fqhank.github.io/fengqianhan.github.io/files/IJCAI2024-Fang.pdf)

Recommended citation:   
@inproceedings{fang2024vccinfuse,  
  title={VCC-INFUSE: Towards Accurate and Efficient Selection of Unlabeled Examples in Semi-supervised Learning},  
  author={Shijie Fang, Qianhan Feng, Tong Lin},  
  booktitle={Proceedings of the International Joint Conference on Artificial Intelligence},    
  year={2024}  
}
