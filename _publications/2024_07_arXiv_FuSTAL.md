---
title: "[Pre-Print] Full-Stage Pseudo Label Quality Enhancement for
Weakly-supervised Temporal Action Localization"
collection: publications
permalink: /publication/2024_07_arXiv_FuSTAL
excerpt: 'Qianhan Feng, Wenshuo Li, Tong Lin*, Xinghao Chen*'
date: 2024-07-15
venue: 'arXiv pre-print'
--- 
**Qianhan Feng**, Wenshuo Li, Tong Lin*, Xinghao Chen* 

Weakly-supervised Temporal Action Localization (WSTAL) aims to localize actions in untrimmed videos using only video-level supervision. Latest WSTAL methods introduce pseudo label learning framework to bridge the gap between classification-based training and inferencing targets at localization, and achieve cutting-edge results. In these frameworks, a classification-based model is used to generate pseudo labels for a regression-based student model to learn from. However, the quality of pseudo labels in the framework, which is a key factor to the final result, is not carefully studied. In this paper, we propose a set of simple yet efficient pseudo label quality enhancement mechanisms to build our FuSTAL framework. FuSTAL enhances pseudo label quality at three stages: cross-video contrastive learning at proposal Generation-Stage, prior-based filtering at proposal Selection-Stage and EMA-based distillation at Training-Stage. These designs enhance pseudo label quality at different stages in the framework, and help produce more informative, less false and smoother action proposals. With the help of these comprehensive designs at all stages, FuSTAL achieves an average mAP of 50.8% on THUMOS'14, outperforming the previous best method by 1.2%, and becomes the first method to reach the milestone of 50%.  
[[Accessible PDF]](https://arxiv.org/pdf/2407.08971)  
[[Code Released]](https://github.com/fqhank/FuSTAL)
