---
title: "Few-Shot Object Detection in Remote-Sensing Images via Label-Consistent Classifier and Gradual Regression"
collection: publications
permalink: /publication/2024-02-26-paper-number-1
excerpt: 'This paper is about addressing the challenges of few-shot object detection in remote-sensing images.'
date: 2024-02-26
venue: 'IEEE Transactions on Geoscience and Remote Sensing'
paperurl: 'https://ieeexplore.ieee.org/document/10445268'
citation: 'Liu, Yanxing, et al. "Few-Shot Object Detection in Remote Sensing Images via Label-Consistent Classifier and Gradual Regression." IEEE Transactions on Geoscience and Remote Sensing (2024).'
---
With the abomination of time-consuming or even impractical large-scale labeling, few-shot object detection (FSOD) based on natural scenes has attracted extensive attention. However, directly migrating FSOD methods designed for natural images to large-size remote-sensing images (RSIs) still remains a challenge. 1) Labels of novel instances within the base dataset are inconsistently assigned between the base training and the few-shot fine-tuning stage, which confuses the detector and leads to significant performance degradation over novel classes. 2) The region proposal network (RPN) of detectors cannot provide sufficient high-quality proposals for remote-sensing objects with various aspect ratios and irregular shapes, leading to decreased detection performance. To tackle these issues, we specify a novel few-shot object detector for RSIs, to avoid the significant performance degradation caused by inconsistent labeling assignments, as well as efficiently leveraging the novel instances that existed in the base dataset. Furthermore, the proposed detector utilizes a coarse-to-fine regression method with an enhanced feature extractor called Gradual RPN to improve the recall of the RPN. Experiments on a newly constructed few-shot detection benchmark show that our approach improves the mAP of novel classes by up to 8.4% and the average recall of the RPN by up to 12.3%. The source code is available at https://github.com/YanxingLiu/SAE-FSDet .
