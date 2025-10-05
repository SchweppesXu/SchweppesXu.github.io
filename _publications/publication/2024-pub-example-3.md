---
title:          "Diffpurifier: An Optical and SAR Image Change Detection Method Based on Diffusion Purification"
date:           2024-05-12 00:01:00 +0800
selected:       true
pub:            "IEEE Transactions on Geoscience and Remote Sensing (TGRS)"
# pub_pre:        "Submitted to "
# pub_post:       ' Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025.6"

abstract: >-
  This article proposes a CD network for optical and SAR images, named Diffpurifier. First, optical images are translated into SAR images using pre-trained denoising diffusion probabilistic models (DDPMs) and ordinary differential equations (ODEs) while simultaneously extracting multiscale features. Then, CD is performed under superpixel enhancement to improve the homogeneity of the CD maps. Diffpurifier not only integrates IT and feature extraction, simplifying the workflow, but also maintains high accuracy, stable training, and generalization to different types of data without the need for additional translation constraints. In comparative experiments on four public datasets, Diffpurifier outperforms the second-best method by an average of approximately 5% in terms of F1 -score, validating the effectiveness and robustness of the method.
cover:          /assets/images/covers/cover1.jpg
authors:
  - <b>Y.Xu</b>
  - X.Su
  - L.Zhang
links:
  Paper: https://ieeexplore.ieee.org/document/11029277
  Code: https://github.com/SchweppesXu/Diffpurifier
---
