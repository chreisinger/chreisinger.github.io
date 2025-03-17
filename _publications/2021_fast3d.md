---
title: "FAST3D: Flow-Aware Self-Training for 3D Object Detectors"
collection: publications
category: conferences
permalink: /publication/fast3d
excerpt: 'In the field of autonomous driving, self-training is widely applied to mitigate distribution shifts in LiDAR-based 3D object detectors. This eliminates the need for expensive, high-quality labels whenever the environment changes (e.g., geographic location, sensor setup, weather condition). State-of-the-art self-training approaches, however, mostly ignore the temporal nature of autonomous driving data. To address this issue, we propose a flow-aware self-training method that enables unsupervised domain adaptation for 3D object detectors on continuous LiDAR point clouds. In order to get reliable pseudo-labels, we leverage scene flow to propagate detections through time. In particular, we introduce a flow-based multi-target tracker, that exploits flow consistency to filter and refine resulting tracks. The emerged precise pseudo-labels then serve as a basis for model re-training. Starting with a pre-trained KITTI model, we conduct experiments on the challenging Waymo Open Dataset to demonstrate the effectiveness of our approach. Without any prior target domain knowledge, our results show a significant improvement over the state-of-the-art.'
date: 2021-11-22
venue: 'British Machine Vision Conference (BMVC)'
paperurl: 'http://https://chreisinger.github.io/files/fast3d.pdf'
citation: 'Fruhwirth-Reisinger, C., Opitz, M., Possegger, H., & Bischof, H. (2021). FAST3D: Flow-Aware Self-Training for 3D Object Detectors. In Proc. of the British Machine Vision Conference (BMVC).'
arxiv: 'https://arxiv.org/abs/2110.09355'
bibtex: '@inproceedings{reisinger2021fast3d,</br>
    &nbsp; &nbsp; &nbsp; title = {{FAST3D: Flow-Aware Self-Training for 3D Object Detectors}},</br> 
    &nbsp; &nbsp; &nbsp; author = {Fruhwirth-Reisinger, Christian and Opitz, Michael and Possegger, Horst and Bischof, Horst},</br>
    &nbsp; &nbsp; &nbsp; booktitle = {Proc. of the British Machine Vision Conference (BMVC)},</br>
    &nbsp; &nbsp; &nbsp; year = {2021}
    </br>}'
authors: 'Christian Fruhwirth-Reisinger, Michael Opitz, Horst Possegger, Horst Bischof'
img: /images/fast3d.png
paperlink: 'https://arxiv.org/pdf/2110.09355'
---

In the field of autonomous driving, self-training is widely applied to mitigate distribution shifts in LiDAR-based 3D object detectors. This eliminates the need for expensive, high-quality labels whenever the environment changes (e.g., geographic location, sensor setup, weather condition). State-of-the-art self-training approaches, however, mostly ignore the temporal nature of autonomous driving data. To address this issue, we propose a flow-aware self-training method that enables unsupervised domain adaptation for 3D object detectors on continuous LiDAR point clouds. In order to get reliable pseudo-labels, we leverage scene flow to propagate detections through time. In particular, we introduce a flow-based multi-target tracker, that exploits flow consistency to filter and refine resulting tracks. The emerged precise pseudo-labels then serve as a basis for model re-training. Starting with a pre-trained KITTI model, we conduct experiments on the challenging Waymo Open Dataset to demonstrate the effectiveness of our approach. Without any prior target domain knowledge, our results show a significant improvement over the state-of-the-art.
