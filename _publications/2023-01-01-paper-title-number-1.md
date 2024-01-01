---
title: "APPLeNet: Visual Attention Parameterized Prompt Learning for Few-Shot Remote Sensing Image Generalization using CLIP"
collection: publications
permalink: /publication/2023-01-01-paper-title-number-1
excerpt: ''
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops'


---
In recent years, the success of large-scale visionlanguage models (VLMs) such as CLIP has led to their increased usage in various computer vision tasks. These models enable zero-shot inference through carefully crafted instructional text prompts without task-specific supervision. However, the potential of VLMs for generalization tasks in remote sensing (RS) has not been fully realized. To address this research gap, we propose a novel image-conditioned prompt learning strategy called the Visual Attention Parameterized Prompts Learning Network (APPLeNet). APPLeNet emphasizes the importance of multi-scale feature learning in RS scene classification and disentangles visual style and content primitives for domain generalization tasks. To achieve this, APPLeNet combines visual content features obtained from different layers of the vision encoder and style properties obtained from feature statistics of domain-specific batches. An attention-driven injection module is further introduced to generate visual tokens from this information. We also introduce an anticorrelation regularizer to ensure discrimination among the token embeddings, as this visual information is combined with the textual tokens. To validate APPLeNet, we curated four available RS benchmarks and introduced experimental protocols and datasets for three domain generalization tasks.

[![paper](https://img.shields.io/badge/arXiv-Paper-brightgreen)](https://openaccess.thecvf.com/content/CVPR2023W/EarthVision/papers/Jha_APPLeNet_Visual_Attention_Parameterized_Prompt_Learning_for_Few-Shot_Remote_Sensing_CVPRW_2023_paper.pdf)
[![supplement](https://img.shields.io/badge/Supplementary-Material-F9D371)](https://openaccess.thecvf.com/content/CVPR2023W/EarthVision/supplemental/Jha_APPLeNet_Visual_Attention_CVPRW_2023_supplemental.pdf)
[![arXiv](https://img.shields.io/badge/arXiv-Paper-brightgreen)](https://arxiv.org/abs/2304.05995)

Please cite the paper if you use our work . Thanks.

```
@inproceedings{singha2023applenet,
  title={Applenet: Visual attention parameterized prompt learning for few-shot remote sensing image generalization using clip},
  author={Singha, Mainak and Jha, Ankit and Solanki, Bhupendra and Bose, Shirsha and Banerjee, Biplab},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2023}
}
```
