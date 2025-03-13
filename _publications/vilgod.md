---
title: "Vision-Language Guidance for LiDAR-based Unsupervised 3D Object Detection"
collection: publications
category: conferences
permalink: /publication/vilgod
excerpt: 'Accurate 3D object detection in LiDAR point clouds is crucial for autonomous driving systems. To achieve state-of-the-art performance, the supervised training of detectors requires large amounts of human-annotated data, which is expensive to obtain and restricted to predefined object categories. To mitigate manual labeling efforts, recent unsupervised object detection approaches generate class-agnostic pseudo-labels for moving objects, subsequently serving as supervision signal to bootstrap a detector. Despite promising results, these approaches do not provide class labels or generalize well to static objects. Furthermore, they are mostly restricted to data containing multiple drives from the same scene or images from a precisely calibrated and synchronized camera setup. To overcome these limitations, we propose a vision-language-guided unsupervised 3D detection approach that operates exclusively on LiDAR point clouds. We transfer CLIP knowledge to classify point clusters of static and moving objects, which we discover by exploiting the inherent spatio-temporal information of LiDAR point clouds for clustering, tracking, as well as box and label refinement. Our approach outperforms state-of-the-art unsupervised 3D object detectors on the Waymo Open Dataset (+23 AP3D) and Argoverse 2 (+7.9 AP3D) and provides class labels not solely based on object size assumptions, marking a significant advancement in the field.'
date: 2024-11-25
venue: 'British Machine Vision Conference (BMVC)'
paperurl: 'http://https://chreisinger.github.io/files/vilgod.pdf'
citation: 'Fruhwirth-Reisinger, C., Opitz, M., Possegger, H., & Bischof, H. (2021). FAST3D: Flow-Aware Self-Training for 3D Object Detectors. In Proc. of the British Machine Vision Conference (BMVC).'
arxiv: 'https://arxiv.org/abs/2408.03790v1'
bibtex: '@inproceedings{reisinger2024vilgod,</br>
    &nbsp; &nbsp; &nbsp; title = {{Vision-Language Guidance for LiDAR-based Unsupervised 3D Object Detection}},</br> 
    &nbsp; &nbsp; &nbsp; author = {Fruhwirth-Reisinger, Christian and Lin, Wei and Malić, Dušan and Possegger, Horst},</br>
    &nbsp; &nbsp; &nbsp; booktitle = {Proc. of the British Machine Vision Conference (BMVC)},</br>
    &nbsp; &nbsp; &nbsp; year = {2024}
    </br>}'
authors: 'Christian Fruhwirth-Reisinger, Wei Lin, Dušan Malić, Horst Bischof, Horst Possegger'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
