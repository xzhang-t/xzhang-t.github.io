---
title: "Unsupervised surface anomaly detection with diffusion probabilistic model"
collection: publications
category: conferences
permalink: /publication/iccv23
excerpt: ''
date: 2023-10-01
venue: 'Proceedings of the IEEE/CVF International Conference on Computer Vision'
paperurl: 'https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_Unsupervised_Surface_Anomaly_Detection_with_Diffusion_Probabilistic_Model_ICCV_2023_paper.pdf'
citation: 'Zhang X, Li N, Li J, et al. Unsupervised surface anomaly detection with diffusion probabilistic model[C]//Proceedings of the IEEE/CVF International Conference on Computer Vision. 2023: 6782-6791.'
---

Unsupervised surface anomaly detection aims at discovering and localizing anomalous patterns using only anomaly-free training samples. Reconstruction-based models are among the most popular and successful methods, which rely on the assumption that anomaly regions are more difficult to reconstruct. However, there are three major challenges to the practical application of this approach: 1) the reconstruction quality needs to be further improved since it has a great impact on the final result, especially for images with structural changes; 2) it is observed that for many neural networks, the anomalies can also be well reconstructed, which severely violates the underlying assumption; 3) since reconstruction is an ill-conditioned problem, a test instance may correspond to multiple normal patterns, but most current reconstruction-based methods have ignored this critical fact. In this paper, we propose DiffAD, a method for unsupervised anomaly detection based on the latent diffusion model, inspired by its ability to generate high-quality and diverse images. We further propose noisy condition embedding and interpolated channels to address the aforementioned challenges in the general reconstruction-based pipeline. Extensive experiments show that our method achieves state-of-the-art performance on the challenging MVTec dataset, especially in localization accuracy.
