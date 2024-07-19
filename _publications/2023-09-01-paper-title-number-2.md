---
title: "HAVE-Net: Hallucinated Audio-Visual Embeddings for Few-Shot Classification with Unimodal Cues"
collection: publications
permalink: /publication/2023-09-01-paper-title-number-2
excerpt: ''
venue: 'European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD) Workshops'
---

Best Paper Award !


Recognition of remote sensing (RS) or aerial images is currently of great interest, and advancements in deep learning algorithms added flavor to it in recent years. Occlusion, intra-class variance, lighting, etc., might arise while training neural networks using unimodal RS
visual input. Even though joint training of audio-visual modalities improves classification performance in a low-data regime, it has yet to be thoroughly investigated in the RS domain. Here, we aim to solve a novel problem where both the audio and visual modalities are present during the meta-training of a few-shot learning (FSL) classifier; however, one of the modalities might be missing during the meta-testing stage. This problem formulation is pertinent in the RS domain, given the difficulties in data acquisition or sensor malfunctioning. To mitigate, we propose a novel few-shot generative framework, Hallucinated Audio-Visual Embeddings-Network (HAVE-Net), to meta-train cross-modal features from limited unimodal data. Precisely, these hallucinated features are meta-learned from base classes and used for few-shot classification on novel classes during the inference phase. The experimental results on the benchmark ADVANCE and AudioSetZSL datasets show that our hallucinated modality augmentation strategy for few-shot classification outperforms the classifier performance trained with the real multimodal information at least by 0.8-2%.

[![arXiv](https://img.shields.io/badge/arXiv-Paper-brightgreen)](https://arxiv.org/abs/2309.13470)
