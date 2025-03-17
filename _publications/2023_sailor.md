---
title: "SAILOR: Scaling Anchors via Insights into Latent Object Representation"
collection: publications
category: conferences
permalink: /publication/sailor
excerpt: 'LiDAR 3D object detection models are inevitably biased towards their training dataset. The detector clearly exhibits this bias when employed on a target dataset, particularly towards object sizes. However, object sizes vary heavily between domains due to, for instance, different labeling policies or geographical locations. State-of-the-art unsupervised domain adaptation approaches outsource methods to overcome the object size bias. Mainstream size adaptation approaches exploit target domain statistics, contradicting the original unsupervised assumption. Our novel unsupervised anchor calibration method addresses this limitation. Given a model trained on the source data, we estimate the optimal target anchors in a completely unsupervised manner. The main idea stems from an intuitive observation: by varying the anchor sizes for the target domain, we inevitably introduce noise or even remove valuable object cues. The latent object representation, perturbed by the anchor size, is closest to the learned source features only under the optimal target anchors. We leverage this observation for anchor size optimization. Our experimental results show that, without any retraining, we achieve competitive results even compared to state-of-the-art weakly-supervised size adaptation approaches. In addition, our anchor calibration can be combined with such existing methods, making them completely unsupervised.
'
date: 2023-01-03
venue: 'Winter Conference on Applications of Computer Vision (WACV)'
paperurl: 'http://https://chreisinger.github.io/files/sailor.pdf'
citation: ' Malić, D., Fruhwirth-Reisinger, C., Possegger, H., & Bischof, H. (2023). SAILOR: Scaling Anchors via Insights into Latent Object Representation. In Proc. of the Winter Conference on Applications of Computer Vision (WACV).'
arxiv: 'https://arxiv.org/abs/2210.07811'
bibtex: '@inproceedings{malic2023sailor,</br>
    &nbsp; &nbsp; &nbsp; title = {{SAILOR: Scaling Anchors via Insights into Latent Object Representation}},</br> 
    &nbsp; &nbsp; &nbsp; author = {Malić, Dušan and Fruhwirth-Reisinger, Christian and Possegger, Horst and Bischof, Horst},</br>
    &nbsp; &nbsp; &nbsp; booktitle = {Proc. of the Winter Conference on Applications of Computer Vision (WACV)},</br>
    &nbsp; &nbsp; &nbsp; year = {2023}
    </br>}'
authors: 'Dušan Malić, Christian Fruhwirth-Reisinger, Horst Possegger, Horst Bischof'
img: /images/sailor.png
paperlink: 'https://openaccess.thecvf.com/content/WACV2023/papers/Malic_SAILOR_Scaling_Anchors_via_Insights_Into_Latent_Object_Representation_WACV_2023_paper.pdf'
code: 'https://github.com/malicd/sailor'
---

LiDAR 3D object detection models are inevitably biased towards their training dataset. The detector clearly exhibits this bias when employed on a target dataset, particularly towards object sizes. However, object sizes vary heavily between domains due to, for instance, different labeling policies or geographical locations. State-of-the-art unsupervised domain adaptation approaches outsource methods to overcome the object size bias. Mainstream size adaptation approaches exploit target domain statistics, contradicting the original unsupervised assumption. Our novel unsupervised anchor calibration method addresses this limitation. Given a model trained on the source data, we estimate the optimal target anchors in a completely unsupervised manner. The main idea stems from an intuitive observation: by varying the anchor sizes for the target domain, we inevitably introduce noise or even remove valuable object cues. The latent object representation, perturbed by the anchor size, is closest to the learned source features only under the optimal target anchors. We leverage this observation for anchor size optimization. Our experimental results show that, without any retraining, we achieve competitive results even compared to state-of-the-art weakly-supervised size adaptation approaches. In addition, our anchor calibration can be combined with such existing methods, making them completely unsupervised.

