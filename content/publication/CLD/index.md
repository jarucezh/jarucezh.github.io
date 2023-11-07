---
title: 'Cross-Level Distillation and Feature Denoising for Cross-Domain Few-Shot Classification'
authors:
  - admin
  - Runqi WANG
  - Jianzhuang LIU
  - Asako KANEZAKI

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

abstract: The conventional few-shot classification aims at learning a model on a large labeled base dataset and rapidly adapting to a target dataset that is from the same distribution as the base dataset. However, in practice, the base and the target datasets of few-shot classification are usually from different domains, which is the problem of cross-domain few-shot classification. We tackle this problem by making a small proportion of unlabeled images in the target domain accessible in the training stage. In this setup, even though the base data are sufficient and labeled, the large domain shift still makes transferring the knowledge from the base dataset difficult. We meticulously design a cross-level knowledge distillation method, which can strengthen the ability of the model to extract more discriminative features in the target dataset by guiding the network's shallow layers to learn higher-level information. Furthermore, in order to alleviate the overfitting in the evaluation stage, we propose a feature denoising operation which can reduce the feature redundancy and mitigate overfitting. Our approach can surpass the previous state-of-the-art method, Dynamic-Distillation, by 5.44% on 1-shot and 1.37% on 5-shot classification tasks on average in the BSCD-FSL benchmark.


date: '2023-05-02T00:00:00Z'
publishDate: '2023-05-02'
publication_short: In *ICLR 2023*
url_pdf: 'https://arxiv.org/abs/2311.02392'
url_code: 'https://github.com/jarucezh/cldfd'


---
