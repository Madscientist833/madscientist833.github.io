---
title: "Fréchet Video Motion Distance: A Metric for Evaluating Motion Consistency in Videos"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Innovatively engineered Frechet Video Motion Distance (FMVD), a novel metric emulating human perception, fo-
cused on evaluating motion consistency and temporal coherence in video generation<br/><img src='/images/500x300.png'>'
date: 2024-06-23
venue: 'CVL Workshop at ICML’24'
paperurl: 'https://arxiv.org/pdf/2407.16124'
citation: 'Jiahe Liu, Youran Qu, Qi Yan, Xiaohui Zeng, Lele Wang, Renjie Liao ”Fréchet Video Motion Distance:
A Metric for Evaluating Motion Consistency in Videos” in ICML’24 Workshop'
---

Significant advancements have been made in video generative models recently. Unlike image generation, video generation presents greater challenges, requiring not only generating high-quality frames but also ensuring temporal consistency across these frames. Despite the impressive progress, research on metrics for evaluating the quality of generated videos, especially concerning temporal and motion consistency, remains underexplored. To bridge this research gap, we propose Fréchet Video Motion Distance (FVMD) metric, which focuses on evaluating motion consistency in video generation. Specifically, we design explicit motion features based on key point tracking, and then measure the similarity between these features via the Fréchet distance. We conduct sensitivity analysis by injecting noise into real videos to verify the effectiveness of FVMD. Further, we carry out a large-scale human study, demonstrating that our metric effectively detects temporal noise and aligns better with human perceptions of generated video quality than existing metrics. Additionally, our motion features can consistently improve the performance of Video Quality Assessment (VQA) models, indicating that our approach is also applicable to unary video quality evaluation.
