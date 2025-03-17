---
title: "GBlobs: Explicit Local Structure via Gaussian Blobs for Improved Cross-Domain LiDAR-based 3D Object Detection"
collection: publications
category: conferences
permalink: /publication/gblobs
excerpt: 'LiDAR-based 3D detectors need large datasets for training, yet they struggle to generalize to novel domains. Domain Generalization (DG) aims to mitigate this by training detectors that are invariant to such domain shifts. Current DG approaches exclusively rely on global geometric features (point cloud Cartesian coordinates) as input features. Over-reliance on these global geometric features can, however, cause 3D detectors to prioritize object location and absolute position, resulting in poor cross-domain performance. To mitigate this, we propose to exploit explicit local point cloud structure for DG, in particular by encoding point cloud neighborhoods with Gaussian blobs, GBlobs. Our proposed formulation is highly efficient and requires no additional parameters. Without any bells and whistles, simply by integrating GBlobs in existing detectors, we beat the current state-of-the-art in challenging single-source DG benchmarks by over 21 mAP (Waymo->KITTI), 13 mAP (KITTI->Waymo), and 12 mAP (nuScenes->KITTI), without sacrificing in-domain performance. Additionally, GBlobs demonstrate exceptional performance in multi-source DG, surpassing the current state-of-the-art by 17, 12, and 5 mAP on Waymo, KITTI, and ONCE, respectively.'
date: 2025-06-11
venue: 'Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'http://https://chreisinger.github.io/files/gblobs.pdf'
citation: 'Malić, D., Fruhwirth-Reisinger, C., Schulter S., & Possegger, H. (2025). GBlobs: Explicit Local Structure via Gaussian Blobs for Improved Cross-Domain LiDAR-based 3D Object Detection. In Proc. of the Conference on Computer Vision and Pattern Recognition (CVPR).'
arxiv: 'https://arxiv.org/abs/2503.08639'
bibtex: '@inproceedings{malic2025gblobs,</br>
    &nbsp; &nbsp; &nbsp; title = {{GBlobs: Explicit Local Structure via Gaussian Blobs for Improved Cross-Domain LiDAR-based 3D Object Detection
}},</br> 
    &nbsp; &nbsp; &nbsp; author = {Malić, Dušan and Fruhwirth-Reisinger, Christian and Schulter, Samuel and Possegger, Horst},</br>
    &nbsp; &nbsp; &nbsp; booktitle = {Proc. of the Conference on Computer Vision and Pattern Recognition (CVPR)},</br>
    &nbsp; &nbsp; &nbsp; year = {2025}
    </br>}'
authors: 'Dušan Malić, Christian Fruhwirth-Reisinger, Samuel Schulter, Horst Possegger'
code: 'https://github.com/malicd/GBlobs'
paperlink: 'https://arxiv.org/pdf/2503.08639'
img: /images/gblobs.png
---

LiDAR-based 3D detectors need large datasets for training, yet they struggle to generalize to novel domains. Domain Generalization (DG) aims to mitigate this by training detectors that are invariant to such domain shifts. Current DG approaches exclusively rely on global geometric features (point cloud Cartesian coordinates) as input features. Over-reliance on these global geometric features can, however, cause 3D detectors to prioritize object location and absolute position, resulting in poor cross-domain performance. To mitigate this, we propose to exploit explicit local point cloud structure for DG, in particular by encoding point cloud neighborhoods with Gaussian blobs, GBlobs. Our proposed formulation is highly efficient and requires no additional parameters. Without any bells and whistles, simply by integrating GBlobs in existing detectors, we beat the current state-of-the-art in challenging single-source DG benchmarks by over 21 mAP (Waymo->KITTI), 13 mAP (KITTI->Waymo), and 12 mAP (nuScenes->KITTI), without sacrificing in-domain performance. Additionally, GBlobs demonstrate exceptional performance in multi-source DG, surpassing the current state-of-the-art by 17, 12, and 5 mAP on Waymo, KITTI, and ONCE, respectively.

