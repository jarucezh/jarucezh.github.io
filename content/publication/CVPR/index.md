---
title: 'Few-Shot Learning with Visual Distribution Calibration and Cross-Modal Distribution Alignment'
authors:
  - Runqi WANG
  - admin
  - Xiaoyue Duan
  - Jianzhuang LIU
  - Yuning LU
  - Tian WANG
  - Songcen XU
  - Baochang ZHANG

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

abstract: Pre-trained vision-language models have inspired much research on few-shot learning. However, with only a few training images, there exist two crucial problems:(1) the visual feature distributions are easily distracted by class-irrelevant information in images, and (2) the alignment between the visual and language feature distributions is difficult. To deal with the distraction problem, we propose a Selective Attack module, which consists of trainable adapters that generate spatial attention maps of images to guide the attacks on class-irrelevant image areas. By messing up these areas, the critical features are captured and the visual distributions of image features are calibrated. To better align the visual and language feature distributions that describe the same object class, we propose a cross-modal distribution alignment module, in which we introduce a vision-language prototype for each class to align the distributions, and adopt the Earth Mover's Distance (EMD) to optimize the prototypes. For efficient computation, the upper bound of EMD is derived. In addition, we propose an augmentation strategy to increase the diversity of the images and the text prompts, which can reduce overfitting to the few-shot training images. Extensive experiments on 11 datasets demonstrate that our method consistently outperforms prior arts in few-shot learning.


date: '2023-06-18T00:00:00Z'
publishDate: '2023-06-18'
publication_short: In *CVPR 2023*
url_pdf: 'https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Few-Shot_Learning_With_Visual_Distribution_Calibration_and_Cross-Modal_Distribution_Alignment_CVPR_2023_paper.pdf'


---
