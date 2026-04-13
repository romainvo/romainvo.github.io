---
title: "Efficient Unrolled Networks for Large-Scale 3D Inverse Problems"
collection: publications
category: conferences
# permalink: /publication/2024-02-17-paper-title-number-4
date: 2026-01-05
venue: 'Conference on Computer Vision and Pattern Recognition (CVPR)'
codeurl: 'https://github.com/romainvo/efficient-unrolling'
paperurl: 'https://arxiv.org/abs/2601.02141'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
header:
    teaser: 'publications/thumbnail_cvpr2026.png'
---

**Abstract** Deep learning-based methods have revolutionized the field of imaging inverse problems, yielding state-of-the-art performance across various imaging domains. The best performing networks incorporate the imaging operator within the network architecture, typically in the form of deep unrolling. However, in large-scale problems, such as 3D imaging, most existing methods fail to incorporate the operator in the architecture due to the prohibitive amount of memory required by global forward operators, which hinders typical patching strategies. In this work, we present a domain partitioning strategy and normal operator approximations that enable the training of end-to-end reconstruction models incorporating forward operators of arbitrarily large problems into their architecture. The proposed method achieves state-of-the-art performance on 3D X-ray cone-beam tomography and 3D multi-coil accelerated MRI, while requiring only a single GPU for both training and inference.
