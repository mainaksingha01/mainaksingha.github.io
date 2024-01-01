---
title: "STYLIP: Multi-Scale Style-Conditioned Prompt Learning for CLIP-Based Domain Generalization"
collection: publications
permalink: /publication/2024-01-01-paper-title-number-6
excerpt: ''
venue: 'IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2024'
citation: '@inproceedings{bose2024stylip,
  title={Stylip: Multi-scale style-conditioned prompt learning for clip-based domain generalization},
  author={Bose, Shirsha and Jha, Ankit and Fini, Enrico and Singha, Mainak and Ricci, Elisa and Banerjee, Biplab},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={5542--5552},
  year={2024}
}'
---

Large-scale foundation models, such as CLIP, have demonstrated impressive zero-shot generalization performance on downstream tasks, leveraging well-designed language prompts. However, these prompt learning techniques
often struggle with domain shift, limiting their generalization capabilities. In our study, we tackle this issue by proposing STYLIP, a novel approach for Domain Generalization (DG) that enhances CLIP’s classification performance across domains. Our method focuses on a domainagnostic prompt learning strategy, aiming to disentangle the
visual style and content information embedded in CLIP’s pre-trained vision encoder, enabling effortless adaptation to novel domains during inference. To achieve this, we introduce a set of style projectors that directly learn the domainspecific prompt tokens from the extracted multi-scale style
features. These generated prompt embeddings are subsequently combined with the multi-scale visual content features learned by a content projector. The projectors are
trained in a contrastive manner, utilizing CLIP’s fixed vision and text backbones. Through extensive experiments conducted in five different DG settings on multiple benchmark datasets, we consistently demonstrate that STYLIP 
outperforms the current state-of-the-art (SOTA) methods.

[![paper](https://img.shields.io/badge/arXiv-Paper-brightgreen)](https://openaccess.thecvf.com/content/WACV2024/papers/Bose_STYLIP_Multi-Scale_Style-Conditioned_Prompt_Learning_for_CLIP-Based_Domain_Generalization_WACV_2024_paper.pdf)
[![supplement](https://img.shields.io/badge/Supplementary-Material-F9D371)](https://openaccess.thecvf.com/content/WACV2024/supplemental/Bose_STYLIP_Multi-Scale_Style-Conditioned_WACV_2024_supplemental.pdf)
[![arXiv](https://img.shields.io/badge/arXiv-Paper-brightgreen)](https://arxiv.org/abs/2302.09251)

Please cite the paper if you use our work . Thanks.

```
@inproceedings{bose2024stylip,
  title={Stylip: Multi-scale style-conditioned prompt learning for clip-based domain generalization},
  author={Bose, Shirsha and Jha, Ankit and Fini, Enrico and Singha, Mainak and Ricci, Elisa and Banerjee, Biplab},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={5542--5552},
  year={2024}
}
}
```
