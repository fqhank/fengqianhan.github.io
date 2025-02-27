---
title: "[CVPR2025] Align-KD: Distilling Cross-Modal Alignment Knowledge for Mobile Vision-Language Model"
collection: publications
permalink: /publication/2025_06_CVPR_AlignKD
excerpt: 'Qianhan Feng, Wenshuo Li, Tong Lin, Xinghao Chen*'
date: 2025-06-21
venue: 'Proceedings of CVPR'
--- 
**Qianhan Feng**, Wenshuo Li, Tong Lin, Xinghao Chen*

Vision-Language Models (VLMs) bring powerful understanding and reasoning capabilities to multimodal tasks. Meanwhile, the great need for capable aritificial intelligence on mobile devices also arises, such as the AI assistant software. Some efforts try to migrate VLMs to edge devices to expand their application scope. Simplifying the model structure is a common method, but as the model shrinks, the trade-off between performance and size becomes more and more difficult. Knowledge distillation (KD) can help models improve comprehensive capabilities without increasing size or data volume. However, most of the existing large model distillation techniques only consider applications on single-modal LLMs, or only use teachers to create new data environments for students. None of these methods take into account the distillation of the most important cross-modal alignment knowledge in VLMs. We propose a method called Align-KD to guide the student model to learn the cross-modal matching that occurs at the shallow layer. The teacher also helps student learn the projection of vision token into text embedding space based on the focus of text. Under the guidance of Align-KD, the 1.7B MobileVLM V2 model can learn rich knowledge from the 7B teacher model with light design of training loss, and achieve an average score improvement of 2.0 across 6 benchmarks under two training subsets respectively.

[[Accessible PDF]](https://fqhank.github.io/fengqianhan.github.io/files/AlignKD-Feng.pdf)
[[Code Released]](https://github.com/fqhank/Align-KD)

Recommended citation:   
@inproceedings{
}
