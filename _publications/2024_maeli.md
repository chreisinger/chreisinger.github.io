---
title: "MAELi: Masked Autoencoder for Large-Scale LiDAR Point Clouds"
collection: publications
category: conferences
permalink: /publication/maeli
excerpt: "The sensing process of large-scale LiDAR point clouds inevitably causes large blind spots, i.e. regions not visible to the sensor. We demonstrate how these inherent sampling properties can be effectively utilized for self-supervised representation learning by designing a highly effective pre-training framework that considerably reduces the need for tedious 3D annotations to train state-of-the-art object detectors. Our Masked AutoEncoder for LiDAR point clouds (MAELi) intuitively leverages the sparsity of LiDAR point clouds in both the encoder and decoder during reconstruction. This results in more expressive and useful initialization, which can be directly applied to downstream perception tasks, such as 3D object detection or semantic segmentation for autonomous driving. In a novel reconstruction approach, MAELi distinguishes between empty and occluded space and employs a new masking strategy that targets the LiDAR's inherent spherical projection. Thereby, without any ground truth whatsoever and trained on single frames only, MAELi obtains an understanding of the underlying 3D scene geometry and semantics. To demonstrate the potential of MAELi, we pre-train backbones in an end-to-end manner and show the effectiveness of our unsupervised pre-trained weights on the tasks of 3D object detection and semantic segmentation."
date: 2024-01-24
venue: 'Winter Conference on Applications of Computer Vision (WACV)'
paperurl: 'http://https://chreisinger.github.io/files/maeli.pdf'
citation: 'Krispel, G., Schinagl, D., Fruhwirth-Reisinger, C., Possegger, H., & Bischof, H. (2024). MAELi: Masked Autoencoder for Large-Scale LiDAR Point Clouds. In Proc. of the Winter Conference on Applications of Computer Vision (WACV).'
arxiv: 'https://arxiv.org/abs/2212.07207'
bibtex: '@inproceedings{krispel2024maeli,</br>
    &nbsp; &nbsp; &nbsp; title = {{MAELi: Masked Autoencoder for Large-Scale LiDAR Point Clouds}},</br> 
    &nbsp; &nbsp; &nbsp; author = {Krispel, Georg and Schinagl, David and Fruhwirth-Reisinger, Christian and Possegger, Horst and Bischof, Horst},</br>
    &nbsp; &nbsp; &nbsp; booktitle = {Proc. of the Winter Conference on Applications of Computer Vision (WACV) },</br>
    &nbsp; &nbsp; &nbsp; year = {2024}
    </br>}'
authors: 'Georg Krispel, David Schinagl, Christian Fruhwirth-Reisinger, Horst Possegger, Horst Bischof'
img: /images/maeli.png
paperlink: 'https://openaccess.thecvf.com/content/WACV2024/papers/Krispel_MAELi_Masked_Autoencoder_for_Large-Scale_LiDAR_Point_Clouds_WACV_2024_paper.pdf'
---

The sensing process of large-scale LiDAR point clouds inevitably causes large blind spots, i.e. regions not visible to the sensor. We demonstrate how these inherent sampling properties can be effectively utilized for self-supervised representation learning by designing a highly effective pre-training framework that considerably reduces the need for tedious 3D annotations to train state-of-the-art object detectors. Our Masked AutoEncoder for LiDAR point clouds (MAELi) intuitively leverages the sparsity of LiDAR point clouds in both the encoder and decoder during reconstruction. This results in more expressive and useful initialization, which can be directly applied to downstream perception tasks, such as 3D object detection or semantic segmentation for autonomous driving. In a novel reconstruction approach, MAELi distinguishes between empty and occluded space and employs a new masking strategy that targets the LiDAR\'s inherent spherical projection. Thereby, without any ground truth whatsoever and trained on single frames only, MAELi obtains an understanding of the underlying 3D scene geometry and semantics. To demonstrate the potential of MAELi, we pre-train backbones in an end-to-end manner and show the effectiveness of our unsupervised pre-trained weights on the tasks of 3D object detection and semantic segmentation.