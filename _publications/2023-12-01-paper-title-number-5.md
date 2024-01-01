---
title: "C-SAW: Self-Supervised Prompt Learning for Image Generalization in Remote Sensing"
collection: publications
permalink: /publication/2023-12-01-paper-title-number-1
excerpt: ''
venue: 'Indian Conference on Computer Vision, Graphics and Image Processing (ICVGIP)'
citation: '@article{bhattacharya2023c,
  title={C-SAW: Self-Supervised Prompt Learning for Image Generalization in Remote Sensing},
  author={Bhattacharya, Avigyan and Singha, Mainak and Jha, Ankit and Banerjee, Biplab},
  journal={arXiv preprint arXiv:2311.15812},
  year={2023}
}'


---
We focus on domain and class generalization problems in analyzing optical remote sensing images, using the large-scale pre-trained
vision-language model (VLM), CLIP. While contrastively trained VLMs show impressive zero-shot generalization performance, their
effectiveness is limited when dealing with diverse domains during training and testing. Existing prompt learning techniques overlook
the importance of incorporating domain and content information into the prompts, which results in a drop in performance while dealing with such multi-domain data. To address these challenges, we
propose a solution that ensures domain-invariant prompt learning while enhancing the expressiveness of visual features. We observe that CLIP’s vision encoder struggles to identify contextual image
information, particularly when image patches are jumbled up. This issue is especially severe in optical remote sensing images, where
land-cover classes exhibit well-defined contextual appearances. To this end, we introduce C-SAW, a method that complements CLIP
with a self-supervised loss in the visual space and a novel prompt learning technique that emphasizes both visual domain and contentspecific features. We keep the CLIP backbone frozen and introduce
a small set of projectors for both the CLIP encoders to train C-SAW contrastively. Experimental results demonstrate the superiority of
C-SAW across multiple remote sensing benchmarks and different generalization tasks.

![csaw](https://github.com/mainaksingha01/C-SAW/blob/master/images/csaw.png)

[![arXiv](https://img.shields.io/badge/arXiv-Paper-brightgreen)](https://arxiv.org/abs/2311.15812)

Please cite the paper if you use our work . Thanks.

```
@article{bhattacharya2023c,
  title={C-SAW: Self-Supervised Prompt Learning for Image Generalization in Remote Sensing},
  author={Bhattacharya, Avigyan and Singha, Mainak and Jha, Ankit and Banerjee, Biplab},
  journal={arXiv preprint arXiv:2311.15812},
  year={2023}
}
```
