---
title: "GOPro: Generate and Optimize Prompts in CLIP using Self-Supervised Learning"
collection: publications
permalink: /publication/2023-11-01-paper-title-number-4
excerpt: ''
venue: 'British Machine Vision Conference (BMVC) 2023'
citation: '@article{singha2023gopro,
  title={GOPRO: Generate and Optimize Prompts in CLIP using Self-Supervised Learning},
  author={Singha, Mainak and Jha, Ankit and Banerjee, Biplab},
  journal={arXiv preprint arXiv:2308.11605},
  year={2023}
}'


---

Large-scale foundation models, such as CLIP, have demonstrated remarkable success in visual recognition tasks by embedding images in a semantically rich space. Selfsupervised learning (SSL) has also shown promise in improving visual recognition by
learning invariant features. However, the combination of CLIP with SSL is found to face challenges due to the multi-task framework that blends CLIP’s contrastive loss and
SSL’s loss, including difficulties with loss weighting and inconsistency among different views of images in CLIP’s output space. To overcome these challenges, we propose a
prompt learning-based model called GOPRO, which is a unified framework that ensures similarity between various augmented views of input images in a shared image-text embedding space, using a pair of learnable image and text projectors atop CLIP, to promote
invariance and generalizability. To automatically learn such prompts, we leverage the visual content and style primitives extracted from pre-trained CLIP and adapt them to the
target task. In addition to CLIP’s cross-domain contrastive loss, we introduce a visual contrastive loss and a novel prompt consistency loss, considering the different views of
the images. GOPRO is trained end-to-end on all three loss objectives, combining the strengths of CLIP and SSL in a principled manner. Empirical evaluations demonstrate
that GOPRO outperforms the state-of-the-art prompting techniques on three challenging domain generalization tasks across multiple benchmarks by a significant margin. C


[![paper](https://img.shields.io/badge/arXiv-Paper-brightgreen)](https://papers.bmvc2023.org/0314.pdf)
[![supplement](https://img.shields.io/badge/Supplementary-Material-F9D371)](https://bmvc2022.mpi-inf.mpg.de/BMVC2023/0314_supp.pdf)
[![arXiv](https://img.shields.io/badge/arXiv-Paper-brightgreen)](https://arxiv.org/abs/2308.11605)

Please cite the paper if you use our work . Thanks.

```
@article{singha2023gopro,
  title={GOPRO: Generate and Optimize Prompts in CLIP using Self-Supervised Learning},
  author={Singha, Mainak and Jha, Ankit and Banerjee, Biplab},
  journal={arXiv preprint arXiv:2308.11605},
  year={2023}
}
```
