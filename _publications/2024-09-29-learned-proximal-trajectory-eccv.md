---
title: "Learned Proximal Trajectory for 3D Sparse-View X-ray Computed Tomography"
collection: publications
category: conferences
# permalink: /publication/2024-02-17-paper-title-number-4
date: 2024-09-29
venue: 'European Conference on Computer Vision (ECCV)'
codeurl: 'https://github.com/romainvo/pnp-learned-proximal-trajectory'
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
header:
    teaser: '/publications/thumbnail_white_eccv24.png'
---

**Abstract** Plug-and-Play algorithms (PnP) have recently emerged as a powerful framework for solving inverse problems in imaging. They leverage the power of Gaussian denoising algorithms to solve complex optimization problems. This work focuses on the challenging task of 3D sparse-view X-ray computed tomography (CT). We propose to replace the Gaussian denoising network in Plug-and-Play with a restoration network, i.e. a network trained to remove arbitrary artifacts. We show that using a restoration prior tailored to the specific inverse problem improves the performances of Plug-and-Play algorithms. Besides, we show that plugging a basic restoration network into a PnP scheme is not sufficient to obtain good results. Thus, we propose a procedure to train the restoration network to be a robust approximation of a proximal operator along a pre-defined optimization trajectory. We demonstrate the effectiveness and scalability of our approach on two 3D Cone-Beam CT datasets and outperform state-of-the-art methods in terms of PSNR.
