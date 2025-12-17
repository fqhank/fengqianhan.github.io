---
title: "[pre-print] Deep Homography for Efficient Stereo Image Compression"
collection: publications
permalink: /publication/2025_11_arxiv_ucagents
excerpt: 'Qianhan Feng, Zhongzhen Huang, Yakun Zhu, Xiaofan Zhang, Qi Dou'
date: 2025-11-15
venue: 'arxiv'
--- 
**Qianhan Feng**, Zhongzhen Huang, Yakun Zhu, Xiaofan Zhang, Qi Dou*

Vision-Language Models (VLMs) show promise in medical diagnosis, yet suffer from reasoning detachment, where linguistically fluent explanations drift from verifiable image evidence, undermining clinical trust. Recent multi-agent frameworks simulate Multidisciplinary Team (MDT) debates to mitigate single-model bias, but open-ended discussions amplify textual noise and computational cost while failing to anchor reasoning to visual evidence, the cornerstone of medical decision-making. We propose UCAgents, a hierarchical multi-agent framework enforcing unidirectional convergence through structured evidence auditing. Inspired by clinical workflows, UCAgents forbids position changes and limits agent interactions to targeted evidence verification, suppressing rhetorical drift while amplifying visual signal extraction. In UCAgents, a one-round inquiry discussion is introduced to uncover potential risks of visual-textual misalignment. This design jointly constrains visual ambiguity and textual noise, a dual-noise bottleneck that we formalize via information theory. Extensive experiments on four medical VQA benchmarks show UCAgents achieves superior accuracy (71.3% on PathVQA, +6.0% over state-of-the-art) with 87.7% lower token cost, the evaluation results further confirm that UCAgents strikes a balance between uncovering more visual evidence and avoiding confusing textual interference. These results demonstrate that UCAgents exhibits both diagnostic reliability and computational efficiency critical for real-world clinical deployment. Code is available at https://github.com/fqhank/UCAgents.
[[Accessible PDF]](https://arxiv.org/pdf/2512.02485)
[[Code Released]](https://github.com/fqhank/UCAgents)

Recommended citation:   
@misc{feng2025ucagentsunidirectionalconvergencevisual,
      title={UCAgents: Unidirectional Convergence for Visual Evidence Anchored Multi-Agent Medical Decision-Making}, 
      author={Qianhan Feng and Zhongzhen Huang and Yakun Zhu and Xiaofan Zhang and Qi Dou},
      year={2025},
      eprint={2512.02485},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2512.02485}, 
}
